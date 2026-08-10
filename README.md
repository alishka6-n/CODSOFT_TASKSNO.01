# CodSoft Data Analytics Internship - Task 1: Data Cleaning & Preprocessing

## 📌 Project Overview
This repository contains the solution for **Task 1: Data Cleaning & Preprocessing** as part of the CodSoft Data Analytics Internship. The goal of this task is to import a raw dataset, inspect its structure, handle missing or inconsistent data, correct data types, and export a clean version ready for further analysis.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Library:** Pandas
- **Environment:** Jupyter Notebook

## 🔑 Key Steps Performed
1. **Data Inspection:** Loaded the dataset and inspected data types, shape, and missing values using `.info()` and `.isnull().sum()`.
2. **Duplicate Handling:** Checked for and removed duplicate rows.
3. **Missing Value Imputation:** Imputed missing numerical values with median strategies and handled missing categorical data appropriately.
4. **Data Type Correction:** Converted categorical columns to `category` type and standardized numerical fields.
5. **Text Cleaning:** Standardized text attributes by stripping leading and trailing whitespaces.
6. **Data Export:** Exported the final cleaned dataset into a structured CSV file (`cleaned_dataset.csv`).
