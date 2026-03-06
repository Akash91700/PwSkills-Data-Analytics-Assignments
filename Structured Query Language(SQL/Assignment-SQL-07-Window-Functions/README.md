# SQL Assignment 07 - Window Functions

## Overview

This assignment focuses on SQL Window Functions used for ranking, running totals, moving averages, and advanced analytics.

Window functions perform calculations across a set of rows related to the current row without collapsing the result set.

---

# Concepts Covered

ROW_NUMBER()  
RANK()  
DENSE_RANK()  
FIRST_VALUE()  
LAST_VALUE()  
CUME_DIST()  
Running totals  
Moving averages  

---

# Example Window Function

SELECT name, salary,
RANK() OVER (ORDER BY salary DESC)
FROM employees;

---

# Files Included

Assignment-SQL-07-Window-Functions-Questions.md  
Assignment-SQL-07-Window-Functions-Solutions.sql  
README.md
