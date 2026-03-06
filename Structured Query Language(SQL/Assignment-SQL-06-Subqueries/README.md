# SQL Assignment 06 - Subqueries

## Overview

This assignment focuses on SQL subqueries, which allow queries to be nested inside other queries.

Subqueries help solve complex problems by breaking them into smaller logical steps.

---

# Concepts Covered

Subqueries  
Aggregate Functions  
Filtering with nested queries  
IN and NOT IN  
Nested SELECT statements  

---

# What is a Subquery?

A subquery is a query inside another SQL query. It is also called a nested query or inner query.

Example:

SELECT *
FROM employees
WHERE salary > (
SELECT AVG(salary)
FROM employees
);

---

# Types of Subqueries

Scalar Subquery  
Multiple-row Subquery  
Correlated Subquery  

---

# Files Included

Assignment-SQL-06-Subqueries-Questions.md  
Assignment-SQL-06-Subqueries-Solutions.sql  
README.md
