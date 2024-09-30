# Online Retail Data Cleaning and Transformation Project

## Overview
This project focuses on cleaning and transforming a dataset containing transactional data for a UK-based online retail company. The data covers transactions between **December 1, 2010**, and **December 9, 2011**, and includes details such as invoice number, stock code, product description, quantity, price, and customer information.

The primary goal of this project is to clean the dataset by handling missing values, removing duplicates, and filtering invalid records, followed by creating new features for further analysis.

## Objectives
1. **Data Cleaning**: 
   - Handle missing values in key columns like `CustomerID` and `Description`.
   - Remove duplicates.
   - Filter out invalid data (negative quantities or prices).
   
2. **Data Transformation**:
   - Convert `InvoiceDate` to a `datetime` object.
   - Create a `TotalPrice` feature to calculate the value of each transaction.

## Project Structure
This repository contains the following files:

- **`online_retail.csv`**: The raw dataset (if allowed to share).
- **`cleaned_online_retail.csv`**: The cleaned and transformed dataset.
- **`data_cleaning.ipynb`**: Jupyter Notebook with all data cleaning and transformation steps.
- **`data_cleaning.py`**: Python script version of the notebook.
- **`report.md`**: A report summarizing the data cleaning process and key findings.
- **License**: States the license under which the project is shared (if applicable).



## How to Use

### 1. Prerequisites
Make sure you have the following Python libraries installed:
- `pandas`
- `numpy`

You can install these libraries using `pip`:
```bash
pip install pandas numpy
