# PDFOTG

<p align="center">

### Portable Local PDF Toolkit for Windows

A simple, fast and privacy-focused PDF utility for everyday document tasks.

</p>

<p align="center">

[![Windows](https://img.shields.io/badge/Windows-64--bit-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#requirements)
[![Portable](https://img.shields.io/badge/Portable-Yes-2ea44f?style=for-the-badge)](#installation)
[![Processing](https://img.shields.io/badge/Processing-Local-6f42c1?style=for-the-badge)](#privacy)
[![Status](https://img.shields.io/badge/Status-Active%20Development-22c55e?style=for-the-badge)](#project-status)

</p>

<p align="center">

[Download](#download) •
[Features](#features) •
[Usage](#how-to-use) •
[FAQ](#faq)

</p>

---

## Overview

**PDFOTG** is a portable PDF toolkit built for Windows.

It brings common PDF tasks into one clean application so you can manage, transform, secure and convert documents without depending on an online PDF-processing website.

PDFOTG is designed around **local document processing**, meaning your files can be processed directly on your own computer.

---

## What is PDFOTG?

PDFOTG is an all-in-one PDF utility for everyday document work.

Instead of using a separate website for every task, PDFOTG puts multiple tools in one place:

```
Open PDFOTG
     ↓
Choose a tool
     ↓
Select your file
     ↓
Set options
     ↓
Process
     ↓
Get your result 

```
Simple workflow. One application.

---

### Why Use PDFOTG?
One app for everyday PDF work
```
No need to switch between multiple websites or applications for basic PDF operations.
```
Local processing
```
Your documents are processed on your own computer instead of requiring a cloud PDF-processing service.
```
Portable
```
No traditional installation process is required for the portable release.
```
Easy to use
```
Select a tool, add your files, configure the options and process.
```
No unnecessary setup
```
The portable package includes the required runtime and processing components.
```
## Features
Tool	What it does
```
Merge PDF	Combine multiple PDFs into one
Split PDF	Split a PDF into separate documents
Remove Pages	Delete selected pages from a PDF
Extract Pages	Create a new PDF from selected pages
Compress PDF	Reduce PDF file size
Rotate PDF	Rotate PDF pages
Watermark PDF	Add a watermark to documents
Protect PDF	Add password protection
Unlock PDF	Process password-protected PDFs using the correct password
PDF → JPG	Convert PDF pages into JPG images
JPG → PDF	Convert JPG images into a PDF
```


## Feature Highlights
Merge PDF

Combine multiple PDF files into a single document.
```
PDF 1
PDF 2
PDF 3
  ↓
Merged PDF
```
---
Split PDF

Break a PDF into separate documents.

Useful for large files, chapters, sections and individual document extraction.

---

Remove Pages

Remove unwanted pages from a PDF.

Useful for blank pages, duplicates or unnecessary content.

---

Extract Pages

Select specific pages and create a new PDF from them.
```
Original:
1 2 3 4 5 6 7 8

Select:
2 4 7

Result:
2 4 7

```

---


Compress PDF

Reduce PDF size for easier storage, sharing and submission.

---

Rotate PDF

Correct the orientation of PDF pages.

Useful for scanned or sideways documents.

---

Watermark PDF

Add a watermark to your document.

Useful for drafts, confidential files, internal documents and ownership marking.

---

Protect PDF

Add password protection to PDF files.

---

Unlock PDF

Process a protected PDF when you have the correct password.

---

PDF → JPG

Convert PDF pages into JPG images.

```
PDF
 ├── Page 1 → JPG
 ├── Page 2 → JPG
 └── Page 3 → JPG
```
---

JPG → PDF

Combine JPG images into a PDF document.

Useful for scanned documents, certificates, notes and photos.

### Download

Download the latest Windows release from:
```
Download the Latest Release
```
PDFOTG is distributed as a portable Windows application.

---

## Requirements

Supported Platform
Windows 64-bit

The portable release includes the components required to run PDFOTG.

You do not need to separately install the application's bundled dependencies for the portable build.

## Installation

PDFOTG does not require a traditional installer.

1. Download

Download the latest release.

2. Extract

Extract the downloaded package to any folder.

Example:

D:\Applications\PDFOTG\

3. Launch

Run:

PDFOTG.exe

PDFOTG will start and open its interface automatically.

---

## How to Use

Using PDFOTG is straightforward:
```
1. Launch PDFOTG
        ↓
2. Choose a PDF tool
        ↓
3. Select your file(s)
        ↓
4. Configure the available options
        ↓
5. Start processing
        ↓
6. Open or save the result
Privacy
```
PDFOTG is designed with local processing in mind.

For normal desktop PDF operations:

Your documents are processed locally.
A third-party PDF-processing account is not required.
Core PDF processing does not require uploading documents to a cloud PDF-processing service.
Temporary processing data is stored locally on your computer.
Generated results are stored locally.

Runtime data is kept under:

```
%LOCALAPPDATA%\PDFOTG
```
Your original document remains in its original location during normal processing.

PDFOTG focuses on local document processing. Other applications, Windows services or the browser itself may use network connectivity independently.

Portable

PDFOTG is designed to be portable.

You can keep the application in a folder such as:

C:\Apps\PDFOTG\

or:

D:\PortableApps\PDFOTG\

The application can then be launched using:
```
PDFOTG.exe
```
---

## User Data

PDFOTG keeps application runtime data separate from the portable application files.

```
Application
    ↓
PDFOTG.exe
    ↓
Local runtime data
    ↓
%LOCALAPPDATA%\PDFOTG
```
---

## Performance

Processing speed depends on:

PDF size
Number of pages
PDF complexity
Image resolution
Selected operation
CPU performance
Available storage

Large and image-heavy PDFs may take longer to process.

# Important Notes

Always keep backups of important documents.

Before performing destructive operations such as:

Remove Pages
Split
Compression
Conversion

verify the generated output before deleting the original.

Password-protected PDFs may require the correct password for processing.

### FAQ
Does PDFOTG upload my PDFs?

The core desktop processing workflow is designed to process your PDFs locally rather than sending them to a remote PDF-processing service.

Do I need an account?

-> No account is required for the core desktop PDF tools.

Do I need to install PHP or other dependencies?

-> Not for the bundled portable release.

Do I need MySQL?

-> No. The portable desktop version uses local application storage.

Can I run PDFOTG without installing it?

-> Yes. PDFOTG is designed as a portable application.




Will PDFOTG change my original file?

The normal processing workflow works with a processing copy rather than intentionally moving or overwriting the original source file.

## Project Status

PDFOTG is an actively developed B.Tech CSE project.

Current tools:
```
✓ Merge PDF
✓ Split PDF
✓ Remove Pages
✓ Extract Pages
✓ Compress PDF
✓ Rotate PDF
✓ Watermark PDF
✓ Protect PDF
✓ Unlock PDF
✓ PDF → JPG
✓ JPG → PDF
```
More tools and improvements may be added in future releases.

### Roadmap

Future updates may include:
```
More PDF tools
More conversion options
OCR improvements
Better previews
UI/UX improvements
Performance improvements
Additional desktop features
Third-Party Components
```
PDFOTG uses third-party software components for document processing.

Each component remains subject to its respective license.

Users and distributors should review the licenses included with the corresponding release.

---

### License

See the LICENSE file for the license applicable to PDFOTG.

Third-party components may have separate licensing terms.

---


Project Information
```
Project: PDFOTG
Platform: Windows 64-bit
Type: Portable PDF Toolkit
Processing: Local
Status: Active Development
```
<p align="center">
PDFOTG

Portable Local PDF Toolkit for Windows

Process your documents locally.
Keep control of your files.

</p>
