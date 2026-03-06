# SQL Assignment 02 - DISTINCT, LIMIT, ORDER BY

## Overview

This assignment focuses on using the SQL DISTINCT keyword along with LIMIT and ORDER BY to retrieve unique records, filter datasets, and analyze order data.

The assignment also introduces query optimization techniques and indexing strategies for improving performance when working with large datasets.

---

# Concepts Covered

## DISTINCT

DISTINCT removes duplicate records from query results and ensures only unique values are returned.

Example:

SELECT DISTINCT product_name
FROM orders;

---

## ORDER BY

ORDER BY sorts the query results based on a column in ascending or descending order.

Example:

SELECT * FROM orders
ORDER BY order_date DESC;

---

## LIMIT

LIMIT restricts the number of rows returned by a query.

Example:

SELECT * FROM orders
ORDER BY order_date DESC
LIMIT 5;

---

## Query Optimization

Optimization techniques include:

- Indexing frequently used columns
- Reducing unnecessary DISTINCT usage
- Filtering data early using WHERE
- Limiting result sets using LIMIT

---

# Files Included

- Assignment-SQL-02-DISTINCT-LIMIT-ORDERBY-Questions.md
- Assignment-SQL-02-DISTINCT-LIMIT-ORDERBY-Solutions.sql
- README.md
