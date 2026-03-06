# SQL Assignment 02 - DISTINCT, LIMIT, ORDER BY

## Objective
To practice SQL queries using DISTINCT, LIMIT, ORDER BY and learn query optimization techniques.

---

# 1. Practical Use of DISTINCT in SQL

## Scenario
You are working with an e-commerce platform and analyzing orders placed by customers.

Table: Orders

| order_id | customer_id | product_name | order_date |
|----------|-------------|--------------|-----------|
| 101 | 200 | Laptop | 2025-01-15 |
| 102 | 201 | Phone | 2025-01-16 |
| 103 | 202 | Laptop | 2025-01-17 |
| 104 | 200 | Tablet | 2025-01-18 |
| 105 | 203 | Phone | 2025-01-19 |
| 106 | 204 | Laptop | 2025-01-20 |

### Questions

1. Write a SQL query to return a list of **unique products ordered by customers**.
2. Write a SQL query to find **how many unique products each customer ordered**.
3. Write a SQL query to **count the number of distinct products ordered on the platform**.
4. Write a SQL query to return the **most recent distinct products ordered**, sorted by order date.

---

# 2. Combining DISTINCT, LIMIT and ORDER BY

Table: Orders

| order_id | customer_id | product_name | order_date |
|----------|-------------|--------------|-----------|
| 101 | 200 | Laptop | 2025-01-15 |
| 102 | 201 | Phone | 2025-01-16 |
| 103 | 202 | Laptop | 2025-01-17 |
| 104 | 200 | Tablet | 2025-01-18 |
| 105 | 203 | Phone | 2025-01-19 |
| 106 | 204 | Laptop | 2025-01-20 |
| 107 | 205 | Phone | 2025-02-01 |
| 108 | 206 | Tablet | 2025-02-02 |

### Questions

1. Write a query to return the **top 2 most recent distinct products ordered**.
2. Write a query to retrieve the **distinct products ordered by customer 200**, sorted by order date.
3. Write a query to retrieve the **top 5 most ordered products based on distinct orders**.
4. Write a query to count **distinct orders for each product**, sorted in descending order.

---

# 3. Optimizing Queries with DISTINCT and Indexing

### Questions

1. Write a SQL query to retrieve **distinct products ordered in the last month**.
2. Explain why using DISTINCT on large datasets can impact performance.
3. Write an optimized query that retrieves **top 3 distinct products ordered by customer 200**.

---

# 4. Query Optimization and Analysis

### Questions

1. Write a SQL query to retrieve the **most popular products ordered in the last 30 days**.
2. Use **EXPLAIN** to analyze query performance.
3. Suggest indexing strategies to improve query performance.

---

# 5. Real-World Scenario and Complex Query

### Scenario
You are working for an online retailer and need to analyze recent orders.

Table: Orders

| order_id | customer_id | product_name | order_date |

### Questions

1. Write a SQL query to retrieve **top 10 most recent distinct products ordered**.
2. Optimize the query assuming the table contains **millions of records**.
3. Modify the query to include the **customer who placed the most recent order for each product**.
