# Task1

# Data Cleaning and Preparation Project

## 📌 Objective

This project focuses on cleaning and preparing a raw dataset for analysis. The dataset may contain:
- Null or missing values
- Duplicate records
- Inconsistent formatting (e.g., date formats, text casing, column naming)

The goal is to deliver a clean, structured, and analysis-ready dataset.

---

## 🛠️ Tools Used

You can use one or both of the following tools for this project:

- **Microsoft Excel**  
  Useful for quick inspection, manual edits, and small-scale data cleaning.

- **Python (Pandas)**  
  Ideal for programmatic and reproducible cleaning of large datasets.

---

## 🧹 Cleaning Steps Overview

### 1. Load the Raw Dataset
- Excel: Open the file directly.
- Python: Use `pandas.read_csv()` or `read_excel()` to load the data.

### 2. Inspect the Data
- Check data types, null values, and summary statistics.
- Identify potential issues such as:
  - Empty or null cells
  - Duplicates
  - Inconsistent date or string formats

### 3. Handle Missing Values
- Options include:
  - Dropping rows/columns with too many nulls
  - Filling missing values with mean, median, mode, or custom values

### 4. Remove Duplicates
- Excel: Use "Remove Duplicates" from the Data tab.
- Python: Use `df.drop_duplicates()`

### 5. Standardize Formats
- Fix inconsistent date formats (e.g., `MM/DD/YYYY` vs `YYYY-MM-DD`)
- Normalize text casing (e.g., title case for names, lower case for emails)
- Rename columns for clarity and consistency

### 6. Save the Cleaned Dataset
- Excel: Save as a new file (e.g., `cleaned_data.xlsx`)
- Python: Use `df.to_csv()` or `to_excel()` to export cleaned data

---

## 📁 Folder Structure (Optional)

