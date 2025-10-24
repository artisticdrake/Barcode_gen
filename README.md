# 📦 Barcode Generator and PDF Automation Tool

## About
**Barcode Generator** is a desktop automation tool developed as part of the *Technical Mailroom Assistant* role at **Fenway Mailroom, Boston University**.  
It recognizes recipient names and tracking numbers from Excel sheets, generates corresponding **Code128 barcodes**, and compiles them into a **print-ready PDF** for labeling and mailroom management.

---

## Features
- Reads Excel files (`.xls` / `.xlsx`) containing package data.  
- Generates **Code128 barcodes** for each tracking number.  
- Exports a clean, organized **PDF** with barcodes and recipient info.  
- Simple **Tkinter GUI** — no command line required.  
- Automatically paginates long barcode lists across multiple pages.  
- Cross-platform (Windows, macOS, Linux).

---

## How It Works
1. Select an Excel file containing tracking numbers and names.  
2. The script extracts data using **Pandas**.  
3. Each tracking number is converted into a **Code128 barcode**.  
4. Barcodes are arranged with names and codes on an **A4 PDF** using **ReportLab**.  
5. The final PDF is saved for printing and used in the mailroom for efficient package tracking.

---

## Tech Stack

| **Component** | **Description** |
|----------------|-----------------|
| **Language** | Python |
| **Interface** | Tkinter GUI |
| **Libraries** | Pandas, Python-Barcode, ReportLab, Pillow |
| **Barcode Type** | Code128 (alphanumeric tracking support) |
| **Output** | PDF with names, barcodes, and tracking numbers |
| **Use Case** | Mailroom automation for package labeling |

---

Excel Input:                →       PDF Output:
---------------------------------------------------------
| Tracking Number | Name |          | 📦 Barcode Image   |
|-----------------|------|          | Name: John Smith   |
| 1Z45A98E03X...  | John |          | Code: 1Z45A98E03X  |
| 9400A110833...  | Mary |          | Name: Mary Brown   |


## 🧾 Role Context

Developed during my time as a **Technical Mailroom Assistant** at **Boston University (Fenway Mailroom)** to automate package labeling, streamline barcode creation, and improve mailroom operational efficiency.  
This project reduced manual input errors and saved significant time in generating tracking labels for daily mail sorting.

---

## 📘 Glossary

| **Term** | **Definition** |
|-----------|----------------|
| **Barcode** | A machine-readable visual pattern used to encode tracking or product data. |
| **Code128** | A high-density barcode format supporting alphanumeric characters; ideal for package tracking numbers. |
| **Tkinter** | Python’s built-in GUI library, used to create the user interface for selecting files and generating PDFs. |
| **Pandas** | A Python data analysis library used here for reading and processing Excel files. |
| **ReportLab** | A powerful PDF generation library that handles barcode layout, text rendering, and page formatting. |
| **Pillow (PIL)** | Python Imaging Library used for handling barcode images and rendering fonts. |
| **Excel Integration** | The process of reading `.xls` or `.xlsx` spreadsheets to extract package details. |
| **PDF Compilation** | Combining barcode images and text labels into one printable document for labeling. |
| **GUI (Graphical User Interface)** | Visual interface that allows users to interact with the program without code commands. |
| **Automation** | The process of eliminating manual work — here, replacing repetitive label creation with one-click execution. |

