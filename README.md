# Data Cleaning Project Using Ms Excel

## Project Overview

This project focuses on **cleaning a messy financial dataset** and transforming it into a structured format that is ready for analysis and visualization.

The goal of this project is to practice real-world **data cleaning skills**, which is one of the most important tasks in data analysis.

---

## Objectives

* Identify and fix data quality issues
* Standardize formats (dates, currency, text)
* Handle missing and incorrect values
* Prepare the dataset for analysis

---

## Dataset Description

The dataset contains financial transaction data with the following fields:

* Transaction ID
* Invoice Date
* Payment Date
* Department
* Company Name
* Category
* Amount
* Currency
* Payment Method
* Region
* Approved By
* Invoice Status

---

## Problems in the Raw Dataset

The original dataset had multiple issues:

* Inconsistent date formats (e.g., `2/28/2024`, `########`)
* Missing or corrupted values
* Inconsistent text (e.g., `HR`, `Human Resources`)
* Mixed currency formats (`USD`, `usd`, `Usd`)
* Incorrect or unclear column names
* Duplicate or inconsistent company names
* Negative values that required validation

---

## Data Cleaning Steps

### 1. Data Collection

* Loaded the dataset into the analysis tool (Ms Excel)

### 2. Data Cleaning

* Fixed missing and corrupted values
* Standardized date format to `YYYY-MM-DD`
* Cleaned text fields (consistent naming)
* Removed or corrected invalid data

### 3. Data Preparation

* Renamed columns for clarity
* Standardized currency to ZAR
* Formatted numerical values (e.g., currency format)
* Ensured consistency across all fields

---

## Final Result

* Clean and structured dataset
* Consistent formatting across all columns
* Ready for data analysis and visualization

---

## Tools Used

* Microsoft Excel

---

## Project Structure

```
 Data-Cleaning-Project
 ┣  finance(two dataset: sheet 1 - raw data, sheet 2 - clean data).csv
 ┗  README.md
```

---
