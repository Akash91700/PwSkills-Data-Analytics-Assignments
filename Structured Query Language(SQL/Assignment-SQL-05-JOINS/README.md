# SQL Assignment 05 - SQL JOINS

## Overview

This assignment focuses on SQL JOIN operations used to combine data from multiple related tables.

The dataset includes the following tables:

Customers  
Orders  
Payments  
Employees

These tables simulate a retail company database used to analyze customer transactions.

---

# Concepts Covered

## INNER JOIN

Returns only rows where a match exists in both tables.

Example:

SELECT *
FROM customers
INNER JOIN orders
ON customers.CustomerID = orders.CustomerID;

---

## LEFT JOIN

Returns all rows from the left table and matching rows from the right table.

---

## RIGHT JOIN

Returns all rows from the right table and matching rows from the left table.

---

## FULL JOIN

Returns all rows from both tables whether matched or not.

---

## CROSS JOIN

Returns all possible combinations of rows between two tables.

---

# Files Included

Assignment-SQL-05-JOINS-Questions.md  
Assignment-SQL-05-JOINS-Solutions.sql  
README.md
