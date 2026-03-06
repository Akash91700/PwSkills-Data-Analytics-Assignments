# SQL Practice Repository

## Overview

This repository contains SQL practice assignments and exercises covering **basic to advanced SQL concepts** used in data analysis and database management.

The goal of this repository is to strengthen practical SQL skills such as querying, data cleaning, joins, aggregation, window functions, and advanced analytics.

SQL (Structured Query Language) is the standard language used to interact with relational databases and perform operations such as retrieving, inserting, updating, and deleting data. ([W3Schools][1])

---

# Topics Covered

### 1. Basic SQL Queries

* SELECT
* WHERE
* ORDER BY
* LIMIT

Example

```sql
SELECT *
FROM employees
WHERE salary > 50000;
```

---

### 2. Aggregation Functions

Aggregation functions summarize data from multiple rows.

Common functions:

* COUNT()
* SUM()
* AVG()
* MAX()
* MIN()

Example

```sql
SELECT department, AVG(salary)
FROM employees
GROUP BY department;
```

The `GROUP BY` clause groups rows with identical values so aggregate calculations can be performed on each group. ([GeeksforGeeks][2])

---

### 3. SQL Joins

SQL joins combine data from multiple related tables using a common column.

Types of joins:

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL JOIN
* CROSS JOIN

Example

```sql
SELECT employees.name, departments.department_name
FROM employees
INNER JOIN departments
ON employees.department_id = departments.department_id;
```

JOIN operations allow data from different tables to be combined into one result set. ([W3Schools][3])

---

### 4. Subqueries

A subquery is a query written inside another SQL query.

Example

```sql
SELECT name
FROM employees
WHERE salary >
(SELECT AVG(salary) FROM employees);
```

Subqueries help solve complex filtering and analytical problems.

---

### 5. Window Functions

Window functions perform calculations across a set of rows related to the current row.

Examples

* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* CUME_DIST()
* FIRST_VALUE()
* LAST_VALUE()

Example

```sql
SELECT name, salary,
RANK() OVER (ORDER BY salary DESC) AS rank_salary
FROM employees;
```

---

### 6. Data Cleaning in SQL

Data cleaning tasks include:

* Handling NULL values
* Removing duplicates
* Standardizing text
* Validating data ranges
* Salary band classification

Example

```sql
UPDATE employees
SET position = 'Unknown'
WHERE position IS NULL;
```

---

# Repository Structure

```
SQL
│
├── Assignment-SQL-01
├── Assignment-SQL-02
├── Assignment-SQL-03
├── Assignment-SQL-04
├── Assignment-SQL-05
├── Assignment-SQL-06
├── Assignment-SQL-07
├── Assignment-SQL-08
│
└── README.md
```

Each assignment contains:

* Questions.md
* Solutions.sql
* Dataset (if applicable)

---

# Skills Demonstrated

* SQL Query Writing
* Data Filtering
* Data Aggregation
* Multi-table Joins
* Subqueries
* Window Functions
* Data Cleaning
* Analytical SQL

---

# Tools Used

* MySQL / PostgreSQL
* SQL Workbench / DBeaver
* GitHub

---

# Purpose of This Repository

This repository is part of my **Data Analytics learning journey**, where I practice solving real-world SQL problems and improve my data analysis skills.

---

# Author

Akash Gautam
Data Analytics Learner

[1]: https://www.w3schools.com/sql/sql_intro.asp?utm_source=chatgpt.com "SQL Introduction"
[2]: https://www.geeksforgeeks.org/sql/sql-group-by/?utm_source=chatgpt.com "SQL GROUP BY"
[3]: https://www.w3schools.com/sql/sql_join.asp?utm_source=chatgpt.com "SQL Joins"
