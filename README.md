# data-cleaning-assignment-mounojit
Data Cleaning Project for Mann Hospitality


# Data Cleaning Assignment – Mounojit Das

## Overview

This project is submitted as part of the Data Cleaning Assignment for Mann Hospitality. It involves cleaning, merging, and converting sales and commission invoice data from various formats into clean and structured Excel files using Python.

---

##  Folder Contents

| File Name                        | Description                                           |
|----------------------------------|-------------------------------------------------------|
| `merge_sales_excel.py`           | Python script to merge multiple Excel files from "Payout Summary & Order Level Sales" folder |
| `convert_commission_pdfs.py`     | Python script to extract and convert commission PDF invoices into structured Excel data |
| `merged_sales_data_cleaned.xlsx` | Final cleaned and merged Excel output of sales data  |
| `commission_invoices_cleaned.xlsx` | Cleaned output of commission invoices extracted from PDFs |
| `README.md`                      | This file, describing the project and steps followed |

---

## ⚙Tools & Libraries Used

- `Python`
- `pandas`
- `pdfplumber`
- `os`, `glob`
- `openpyxl`

---

## Steps Performed

1. **Merged Excel Files**  
   - Loaded multiple Excel files containing order-level and payout data  
   - Appended them into a single DataFrame  
   - Saved to `merged_sales_data_cleaned.xlsx`

2. **Converted Commission PDF Invoices**  
   - Used `pdfplumber` to extract tables from 12 commission PDF files  
   - Cleaned and structured the data  
   - Saved to `commission_invoices_cleaned.xlsx`

3. **Output Format**  
   - All outputs are clean `pandas` DataFrames saved in Excel format  
   - Column like `Source_File` added for traceability

---

## Submission

- GitHub Repository: [Paste your GitHub link here]
- ZIP File Name: `Mounojit_Das_Data_Cleaning_Assignment.zip`
- Submitted via email to: `ashish.maan@mannhospitality.com` & CC to `amruthbv@mannhospitality.com`

---

## Thank You

Thank you for reviewing this submission. Looking forward to your feedback!

**Mounojit Das**        
