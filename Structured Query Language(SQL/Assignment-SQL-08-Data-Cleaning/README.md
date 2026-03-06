# SQL Assignment 08 - Data Cleaning

## Overview

This assignment focuses on cleaning and preparing employee data using SQL queries.

The tasks involve identifying missing values, fixing inconsistent data, removing duplicates, and analyzing salary distributions.

---

# Concepts Covered

NULL handling  
Data cleaning  
Duplicate detection  
Data normalization  
Salary classification  
Percentile analysis  

---

# Handling NULL Values

SQL provides several functions to handle NULL values.

Examples:

COALESCE()  
ISNULL()  
IFNULL()

Example:

SELECT COALESCE(salary,0)
FROM employees;

---

# Salary Band Classification

CASE statements can be used to classify data.

Example:

SELECT name,
CASE
WHEN salary < 50000 THEN 'Low'
WHEN salary BETWEEN 50000 AND 100000 THEN 'Medium'
ELSE 'High'
END AS salary_band
FROM employees;

---

# Files Included

Assignment-SQL-08-Data-Cleaning-Questions.md  
Assignment-SQL-08-Data-Cleaning-Solutions.sql  
README.md
