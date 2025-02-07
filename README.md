# **Author:** Makhosetive Sibanda 
# **Title:** PDF-TO-CSV-CONVERTER

## Overview

This repository contains two Python scripts for extracting data from PDF files. The two scripts are :
- PyPDF2
- pdfplumber

## Files:

### 1. **pdf_to_csv_script.ipynb**
This script uses the `PyPDF2` library to extract text from PDF files. Due to its shortcomings of failing to extract tables had to opt for an alternative way

### 2. **pdf_to_csv.ipynb**
This script uses the `pdfplumber` library as it supports extraction of tables

## Requirements:
To run these scripts, you’ll need to install the necessary libraries. You can install them using `pip`:

```bash
pip install PyPDF2 pdfplumber pandas