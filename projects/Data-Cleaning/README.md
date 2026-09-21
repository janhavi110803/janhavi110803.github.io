# SQL Data Cleaning

## 📌 Project Overview

This project focuses on cleaning and preparing a real-world layoffs dataset using MySQL.

The main goal is to transform raw and inconsistent data into a clean and structured dataset that can be used for further analysis.

## 🎯 Objectives

- Remove duplicate records
- Handle missing and null values
- Standardize inconsistent data
- Correct formatting issues
- Prepare the dataset for exploratory data analysis

## 🛠️ Tools & Technologies

- MySQL
- SQL
- MySQL Workbench

## 🔍 Data Cleaning Steps

### 1. Created a Staging Table

A staging table was created to work on the raw dataset without modifying the original data.

### 2. Removed Duplicate Records

Duplicate records were identified using SQL window functions and removed from the dataset.

### 3. Standardized Data

Inconsistent company names, industries and other values were standardized to improve data consistency.

### 4. Handled Missing Values

Missing and blank values were identified and handled where appropriate.

### 5. Standardized Dates

Date values were converted into a consistent date format for easier analysis.

### 6. Removed Unnecessary Records

Records that were not useful for analysis were removed.

### 7. Verified the Cleaned Dataset

The final dataset was checked to ensure that the cleaning process was successful.

## 💡 SQL Concepts Used

- SELECT
- UPDATE
- DELETE
- ALTER TABLE
- GROUP BY
- JOIN
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()
- TRIM()
- NULL handling

## 📊 Dataset

The project uses a layoffs dataset containing information such as:

- Company
- Location
- Industry
- Total Laid Off
- Percentage Laid Off
- Date
- Stage
- Country
- Funds Raised

## 📁 Project Files

- `Data Cleaning.sql` — SQL queries used for data cleaning
- `README.md` — Project documentation

## 🚀 Conclusion

The raw dataset was cleaned and transformed into a more consistent and analysis-ready format.

This project helped strengthen my practical understanding of SQL, MySQL and data preprocessing.

## 👩‍💻 Author

Janhavi Chaudhari

MCA Student | Aspiring Data Analyst
