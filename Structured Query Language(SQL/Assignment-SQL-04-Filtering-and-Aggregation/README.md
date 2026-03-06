# SQL Assignment 04 - Filtering and Aggregation

## Overview

This assignment focuses on filtering data using SQL conditions and analyzing sales transaction data using aggregation functions.

Students will practice using:

- WHERE clause
- Logical operators (AND, OR)
- ORDER BY
- GROUP BY
- HAVING
- Aggregate functions

---

# Concepts Covered

## WHERE Clause
Filters rows based on conditions.

Example:

SELECT *
FROM sales_transactions
WHERE amount > 1000;

---

## GROUP BY
Groups rows with the same values and allows aggregate functions.

Example:

SELECT category, COUNT(*)
FROM sales_transactions
GROUP BY category;

---

## HAVING
Filters grouped data after aggregation.

Example:

SELECT category, COUNT(*)
FROM sales_transactions
GROUP BY category
HAVING COUNT(*) > 3;

---

## ORDER BY
Sorts query results.

Example:

SELECT *
FROM sales_transactions
ORDER BY amount DESC;

---

# Files Included

- Assignment-SQL-04-Questions.md
- Assignment-SQL-04-Solutions.sql
- README.md
