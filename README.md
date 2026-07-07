# 🧹 Data Cleaning & Preparation – Online Retail II Dataset (UK 2009)

## 📌 Project Overview

This project demonstrates the complete data cleaning process for the **Online Retail II** dataset. The goal was to improve data quality by identifying and resolving common issues before performing any analysis.

The original dataset was filtered to include only **United Kingdom** transactions from **2009**, creating a focused dataset for cleaning and future analysis.

---

## 📂 Dataset

- **Dataset:** Online Retail II (UCI/Kaggle) https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci
- **Country:** United Kingdom
- **Year:** 2009
- **Tool Used:** Google Sheets/Excel

---

## 🎯 Objective

The objective of this project was to prepare a raw retail transaction dataset for analysis by:

- Removing duplicate records
- Removing cancelled transactions
- Handling incomplete records
- Cleaning text fields
- Verifying data consistency
- Preserving valid business information

---

## 🛠 Data Cleaning Steps

The following cleaning operations were performed:

- Created a separate working copy of the dataset
- Filtered the dataset to include only UK transactions from 2009
- Removed duplicate rows
- Removed cancelled invoices (Invoice numbers beginning with **C**)
- Removed rows with missing product descriptions and zero unit price
- Removed completely blank rows
- Removed unnecessary spaces from text fields
- Standardized text formatting where required
- Verified numeric data types
- Standardized date & time formatting
- Reviewed missing values across all columns

---

## ✅ Data Retained

The following records were intentionally retained to preserve valuable business information:

- Missing Customer IDs (could not be reliably inferred)
- Valid zero-priced products (likely promotional or complimentary items)
- Valid sales transactions containing complete product information

---

## 📊 Dataset Before & After

| Metric | Before | After |
|---------|--------|-------|
| Total Rows | 42857  | 41235 |
| Duplicate Rows Removed | 502+ | 0 |
| Cancelled Orders Removed | 868 | 0 |
  13125 blank customer ids with useful info
  91 returned products
  28 0 price 



---

## 📁 Project Structure

```
Data-Cleaning-Project/
│
│  
│
├── cleaned.xlsx (cleaned data)
│   
│
├── report.docx
```

---

## 📈 Skills Demonstrated

- Data Cleaning
- Data Validation
- Handling Missing Values
- Duplicate Removal
- Data Quality Assessment
- Spreadsheet Functions
- Google Sheets
- Advanced Excel
- Data Preparation
- Business Analysis

---

## 🚀 Future Improvements

The cleaned dataset will be used for:

- Exploratory Data Analysis (EDA)
- Excel Pivot Tables
- Interactive Dashboards
- Power BI Visualizations
- Business Insights

---

## 👤 Author

**Md Afaq Ali Ahmed** https://www.linkedin.com/in/afaq-ahmed-1837163aa/

Aspiring Data Analyst passionate about transforming raw data into meaningful insights using Excel, SQL, Power BI, Python, and AI tools.

---

⭐ If you found this project helpful, feel free to star the repository. 
