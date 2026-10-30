# Awesome PDF with stars

A curated list of resources around PDF files

## The File Format

* PDF Association: [PDF Specification Index](https://www.pdfa.org/resource/pdf-specification-index/), 2021.
* Jindrich Kubec, Jiri Sejtko: [X is not enough! Grab the PDF by the tail!](https://www.virusbulletin.com/uploads/pdf/conference_slides/2011/Kubec-Sejtko-VB2011.pdf) at [Virus Bulletin](https://www.virusbulletin.com/), 2011.
* Selected compilation of PDF Standards from the [Adobe Open Source Reference](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/acrobatsdk/#pdf-reference), 2022.
  1. [PDF Reference 1.0](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.0.pdf)
  2. [PDF Reference 1.2](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.2.pdf)
  3. [PDF Reference 1.3](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.3.pdf)
  4. [PDF Reference 1.4](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.4.pdf)
  5. [PDF Reference 1.5 (v6)](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.5_v6.pdf)
  6. [PDF Reference 1.6](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/pdfreference1.6.pdf)
  7. [PDF Reference 1.7 (ISO 32000, 2008)](https://web.archive.org/web/20220827074128/https://opensource.adobe.com/dc-acrobat-sdk-docs/pdfstandards/PDF32000_2008.pdf)
  8. [PDF Reference 2.0 (ISO 32000-2:2020)](https://www.pdfa-inc.org/product/iso-32000-2-pdf-2-0-bundle-sponsored-access/) (freely available ISO standard due to corporate sponsorship)
* Adobe: [XMP Specification Part 3](https://github.com/adobe/xmp-docs/blob/master/XMPSpecifications/XMPSpecificationPart3.pdf) ⭐ 59 | 🐛 9 | 📅 2024-06-02, January 2020.

## Viewers

* [KOReader](https://github.com/koreader/koreader) ⭐ 30,739 | 🐛 1,395 | 🌐 Lua | 📅 2026-10-29: a document viewer primarily aimed at e-ink readers also available on Android
* [Librera FD](https://github.com/foobnix/LibreraReader) ⭐ 4,977 | 🐛 530 | 🌐 C | 📅 2026-10-29: a document viewer for Android with customizable text-to-speech
* [vue-pdf](https://github.com/FranckFreiburger/vue-pdf) ⭐ 2,293 | 🐛 254 | 🌐 JavaScript | 📅 2024-07-24: vue.js pdf viewer
* [react-native-pdf](https://github.com/wonday/react-native-pdf) ⭐ 1,816 | 🐛 396 | 🌐 JavaScript | 📅 2026-08-20: a react native PDF view component
* [PdfViewPager](https://github.com/voghDev/PdfViewPager) ⭐ 1,715 | 🐛 43 | 🌐 Java | 📅 2026-09-21: Android widget to display PDF documents in your Activities or Fragments
* [ng2-pdfjs-viewer](https://github.com/intbot/ng2-pdfjs-viewer) ⭐ 253 | 🐛 42 | 🌐 JavaScript | 📅 2026-10-26: a comprehensive Angular PDF viewer built on PDF.js with annotations, forms, signatures, search, and read-aloud

## Data Extraction

* [xberg](https://github.com/xberg-io/xberg) ⭐ 9,464 | 🐛 21 | 🌐 Rust | 📅 2026-10-30: a Rust-core document intelligence framework that extracts text, tables, metadata, and images from PDFs and 97+ formats, with optional Tesseract OCR and bindings for 11 languages.
* [Tabula](https://github.com/tabulapdf/tabula) ⭐ 7,492 | 🐛 541 | 🌐 CSS | 📅 2025-03-14: an application for extracting tables
* [camelot](https://github.com/atlanhq/camelot) ⚠️ Archived: PDF Table Extraction
* [invoice2data](https://github.com/invoice-x/invoice2data) ⭐ 2,241 | 🐛 20 | 🌐 Python | 📅 2026-10-27: Swiss-army knife for structured data extraction from pdf documents.
* [awesome-document-understanding](https://github.com/tstanislawek/awesome-document-understanding) ⭐ 1,545 | 🐛 15 | 📅 2023-06-02: A curated list of resources for Document Understanding (DU) topic
* [pdftotext](https://manpages.debian.org/stretch/poppler-utils/pdftotext.1.en.html): an application that converts Portable Document Format (PDF) files to plain text. Part of poppler-utils.
* [pdfminer.six](https://pypi.org/project/pdfminer.six/): a Python library for extracting information from PDF documents
  * [pdfplumber](https://github.com/jsvine/pdfplumber) ⭐ 10,854 | 🐛 123 | 🌐 Python | 📅 2026-10-15: Plumb a PDF for detailed information about each text character, rectangle, and line. Plus: Table extraction and visual debugging.

## Generators

Anything that can produce PDF files from scratch:

* [react-pdf](https://github.com/diegomura/react-pdf) ⭐ 16,847 | 🐛 361 | 🌐 TypeScript | 📅 2026-10-29: Create PDF files using React
* [prawn](https://github.com/prawnpdf/prawn) ⭐ 4,824 | 🐛 96 | 🌐 Ruby | 📅 2026-04-18: a pure Ruby PDF generation library
* [mpdf](https://github.com/mpdf/mpdf) ⭐ 4,704 | 🐛 366 | 🌐 PHP | 📅 2026-10-26: PHP library generating PDF files from UTF-8 encoded HTML
* [markdown-pdf](https://github.com/alanshaw/markdown-pdf) ⭐ 2,881 | 🐛 91 | 🌐 JavaScript | 📅 2023-10-19: Markdown to PDF converter
* [fpdf2](https://pypi.org/project/fpdf2/): An Open Source Python library for generating PDFs
* pdflatex (e.g. in [TexLive](https://www.tug.org/texlive/)): A LaTeX-to-PDF converter
* [reportlab](https://pypi.org/project/reportlab/): An Open Source Python library for generating PDFs and graphics.

## Manipulators

Anything that's used to edit an existing PDF file:

* [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) ⭐ 35,192 | 🐛 68 | 🌐 Python | 📅 2026-10-25: adds an OCR text layer to scanned PDF files, allowing them to be searched
* [pdfarranger](https://github.com/pdfarranger/pdfarranger) ⭐ 6,006 | 🐛 92 | 🌐 Python | 📅 2026-10-01: a small python-gtk application, which helps the user to merge or split pdf documents and rotate, crop and rearrange their pages using a graphical interface

## File Analysis / Security

* [Malicious PDF Generator](https://github.com/jonaslejon/malicious-pdf) ⭐ 4,501 | 🐛 4 | 🌐 Python | 📅 2026-10-17: generate a bunch of malicious pdf files with phone-home functionality
* [Pdfalyzer](https://github.com/michelcrypt4d4mus/pdfalyzer) ⭐ 397 | 🐛 4 | 🌐 Python | 📅 2026-02-07: PDF analysis tool to visualize the internal data structure of a PDF in large and colorful diagrams as well as scanning the binary streams embedded in the PDF against a collection of malicious PDF specific YARA rules.
* [pdfbox](https://pdfbox.apache.org/1.8/commandline.html): tool in java to browse internally a pdf. [Download](https://pdfbox.apache.org/download.cgi) and use as `pdfbox-app-x.y.z.jar debug pdf_file`

## Multi-Purpose Libraries

* [PyMuPDF](https://github.com/pymupdf/PyMuPDF) ⭐ 11,016 | 🐛 70 | 🌐 Python | 📅 2026-10-29 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-render-inactive): Python bindings to MuPDF.
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) ⭐ 8,889 | 🐛 107 | 🌐 Go | 📅 2026-10-28 ![](https://shields.io/badge/-extract-inactive)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): batch processing and scripting via a rich command line
* [pdf-lib](https://github.com/Hopding/pdf-lib) ⭐ 8,663 | 🐛 318 | 🌐 TypeScript | 📅 2024-07-17  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): Create and modify PDF documents in any JavaScript environment
* [borb](https://github.com/jorisschellekens/borb) ⭐ 3,572 | 🐛 11 | 🌐 Python | 📅 2026-08-26 ![](https://shields.io/badge/-extract-inactive)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): reading, creating and manipulating PDF files in python
* [pikepdf](https://github.com/pikepdf/pikepdf) ⭐ 2,818 | 🐛 19 | 🌐 Python | 📅 2026-10-25 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive): a Python library for reading and writing PDF, powered by qpdf
* [pdf\_oxide](https://github.com/yfedoseev/pdf_oxide) ⭐ 1,150 | 🐛 317 | 🌐 Rust | 📅 2026-10-30 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): Fast PDF toolkit written in Rust with bindings for Python, Go, JavaScript/TypeScript, C#/.NET, Java, PHP, Ruby, and WASM. Text extraction, image extraction, markdown conversion, PDF creation and editing. MIT/Apache-2.0 licensed.
* [pypdfium2](https://github.com/pypdfium2-team/pypdfium2) ⭐ 849 | 🐛 4 | 🌐 Python | 📅 2026-10-29 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive) ![](https://shields.io/badge/-render-inactive): Python bindings to PDFium.
* [pdftk](https://www.pdflabs.com/tools/pdftk-server/): command-line tool for working with PDFs. It is commonly used for client-side scripting or server-side processing of PDFs.
* [pypdf](https://pypi.org/project/pypdf/) ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive): a free and open-source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files
* [HexaPDF](https://hexapdf.gettalong.org): ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): A pure Ruby PDF creation and manipulation library

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-30._
