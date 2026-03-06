# SQL Assignment 03 - Aggregation and Sakila Queries

## Overview

This assignment focuses on SQL aggregation functions and analytical queries using both a generic country dataset and the Sakila sample database.

The Sakila database is a sample MySQL database representing a DVD rental store system and is commonly used for SQL practice and tutorials.

---

# Concepts Covered

## Aggregate Functions

Aggregate functions perform calculations on multiple rows.

Examples:

SUM()
COUNT()
AVG()
MAX()
MIN()

Example:

SELECT SUM(amount)
FROM payment;

---

## GROUP BY

GROUP BY groups rows that have the same values in specified columns.

Example:

SELECT customer_id, COUNT(*)
FROM rental
GROUP BY customer_id;

---

## ORDER BY

ORDER BY sorts query results.

Example:

SELECT *
FROM payment
ORDER BY payment_date DESC;

---

# Sakila Database Tables Used

customer
rental
payment
staff

These tables store information about customers, movie rentals, and payments.

---

# Files Included

Assignment-SQL-03-Questions.md  
Assignment-SQL-03-Solutions.sql  
README.md
