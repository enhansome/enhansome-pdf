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
* Adobe: [XMP Specification Part 3](https://github.com/adobe/xmp-docs/blob/master/XMPSpecifications/XMPSpecificationPart3.pdf) ⭐ 60 | 🐛 9 | 📅 2024-06-02, January 2020.

## Viewers

* [KOReader](https://github.com/koreader/koreader) ⭐ 29,360 | 🐛 1,325 | 🌐 Lua | 📅 2026-08-29: a document viewer primarily aimed at e-ink readers
* [vue-pdf](https://github.com/FranckFreiburger/vue-pdf) ⭐ 2,297 | 🐛 254 | 🌐 JavaScript | 📅 2024-07-24: vue.js pdf viewer
* [react-native-pdf](https://github.com/wonday/react-native-pdf) ⭐ 1,809 | 🐛 386 | 🌐 JavaScript | 📅 2026-08-20: a react native PDF view component
* [PdfViewPager](https://github.com/voghDev/PdfViewPager) ⭐ 1,717 | 🐛 46 | 🌐 Java | 📅 2021-09-14: Android widget to display PDF documents in your Activities or Fragments

## Data Extraction

* [Tabula](https://github.com/tabulapdf/tabula) ⭐ 7,476 | 🐛 541 | 🌐 CSS | 📅 2025-03-14: an application for extracting tables
* [camelot](https://github.com/atlanhq/camelot) ⚠️ Archived: PDF Table Extraction
* [awesome-document-understanding](https://github.com/tstanislawek/awesome-document-understanding) ⭐ 1,537 | 🐛 12 | 📅 2023-06-02: A curated list of resources for Document Understanding (DU) topic
* [pdftotext](https://manpages.debian.org/stretch/poppler-utils/pdftotext.1.en.html): an application that converts Portable Document Format (PDF) files to plain text. Part of poppler-utils.
* [pdfminer.six](https://pypi.org/project/pdfminer.six/): a Python library for extracting information from PDF documents
  * [pdfplumber](https://github.com/jsvine/pdfplumber) ⭐ 10,701 | 🐛 98 | 🌐 Python | 📅 2026-08-06: Plumb a PDF for detailed information about each text character, rectangle, and line. Plus: Table extraction and visual debugging.

## Generators

Anything that can produce PDF files from scratch:

* [react-pdf](https://github.com/diegomura/react-pdf) ⭐ 16,763 | 🐛 309 | 🌐 TypeScript | 📅 2026-08-27: Create PDF files using React
* [prawn](https://github.com/prawnpdf/prawn) ⭐ 4,820 | 🐛 92 | 🌐 Ruby | 📅 2026-04-18: a pure Ruby PDF generation library
* [mpdf](https://github.com/mpdf/mpdf) ⭐ 4,701 | 🐛 359 | 🌐 PHP | 📅 2026-06-11: PHP library generating PDF files from UTF-8 encoded HTML
* [markdown-pdf](https://github.com/alanshaw/markdown-pdf) ⭐ 2,876 | 🐛 92 | 🌐 JavaScript | 📅 2023-10-19: Markdown to PDF converter
* [fpdf2](https://pypi.org/project/fpdf2/): An Open Source Python library for generating PDFs
* pdflatex (e.g. in [TexLive](https://www.tug.org/texlive/)): A LaTeX-to-PDF converter
* [reportlab](https://pypi.org/project/reportlab/): An Open Source Python library for generating PDFs and graphics.

## Manipulators

Anything that's used to edit an existing PDF file:

* [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) ⭐ 34,611 | 🐛 97 | 🌐 Python | 📅 2026-08-29: adds an OCR text layer to scanned PDF files, allowing them to be searched
* [pdfarranger](https://github.com/pdfarranger/pdfarranger) ⭐ 5,821 | 🐛 84 | 🌐 Python | 📅 2026-08-14: a small python-gtk application, which helps the user to merge or split pdf documents and rotate, crop and rearrange their pages using a graphical interface

## File Analysis / Security

* [Malicious PDF Generator](https://github.com/jonaslejon/malicious-pdf) ⭐ 4,291 | 🐛 4 | 🌐 Python | 📅 2026-08-27: generate a bunch of malicious pdf files with phone-home functionality
* [Pdfalyzer](https://github.com/michelcrypt4d4mus/pdfalyzer) ⭐ 396 | 🐛 5 | 🌐 Python | 📅 2026-02-07: PDF analysis tool to visualize the internal data structure of a PDF in large and colorful diagrams as well as scanning the binary streams embedded in the PDF against a collection of malicious PDF specific YARA rules.
* [pdfbox](https://pdfbox.apache.org/1.8/commandline.html): tool in java to browse internally a pdf. [Download](https://pdfbox.apache.org/download.cgi) and use as `pdfbox-app-x.y.z.jar debug pdf_file`

## Multi-Purpose Libraries

* [PyMuPDF](https://github.com/pymupdf/PyMuPDF) ⭐ 10,602 | 🐛 55 | 🌐 Python | 📅 2026-08-27 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-render-inactive): Python bindings to MuPDF.
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) ⭐ 8,807 | 🐛 115 | 🌐 Go | 📅 2026-08-24 ![](https://shields.io/badge/-extract-inactive)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): batch processing and scripting via a rich command line
* [pdf-lib](https://github.com/Hopding/pdf-lib) ⭐ 8,608 | 🐛 316 | 🌐 TypeScript | 📅 2024-07-17  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): Create and modify PDF documents in any JavaScript environment
* [borb](https://github.com/jorisschellekens/borb) ⭐ 3,570 | 🐛 10 | 🌐 Python | 📅 2026-08-26 ![](https://shields.io/badge/-extract-inactive)  ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): reading, creating and manipulating PDF files in python
* [pikepdf](https://github.com/pikepdf/pikepdf) ⭐ 2,798 | 🐛 20 | 🌐 Python | 📅 2026-08-18 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive): a Python library for reading and writing PDF, powered by qpdf
* [pypdfium2](https://github.com/pypdfium2-team/pypdfium2) ⭐ 814 | 🐛 3 | 🌐 Python | 📅 2026-08-29 ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive) ![](https://shields.io/badge/-render-inactive): Python bindings to PDFium.
* [pdftk](https://www.pdflabs.com/tools/pdftk-server/): command-line tool for working with PDFs. It is commonly used for client-side scripting or server-side processing of PDFs.
* [pypdf](https://pypi.org/project/pypdf/) ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive): a free and open-source pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files
* [HexaPDF](https://hexapdf.gettalong.org): ![](https://shields.io/badge/-extract-inactive) ![](https://shields.io/badge/-manipulate-inactive) ![](https://shields.io/badge/-create-inactive): A pure Ruby PDF creation and manipulation library

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
