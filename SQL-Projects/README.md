# 🛍 Retail Store Sales Analysis Using SQL

## Project Overview

This project demonstrates how SQL can be used to analyze retail sales data and answer real business questions.

The analysis includes filtering, aggregation, Common Table Expressions (CTEs), subqueries, and window functions to generate meaningful business insights.

---

# Business Problem

Retail companies collect thousands of sales transactions every day. Business managers need reports that identify:

- Top customers
- Highest sales
- Monthly performance
- Product category contribution
- Sales trends

SQL allows these questions to be answered efficiently.

---

# Dataset

The dataset contains retail order information including:

- Order ID
- Customer ID
- Sales Amount
- Order Date
- Product Category

---

# Tools Used

- SQL
- SQLite
- SQLiteviz

---

# SQL Concepts Demonstrated

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- Aggregate Functions
- Subqueries
- CTEs
- ROW_NUMBER()
- RANK()
- LAG()
- Running Totals
- Window Functions

---

# Project Tasks

## Question 1
Find all orders where the sales amount is greater than the average sales amount.

**Skills Used**

- Subquery
- AVG()

**Business Insight**

Only high-value transactions are returned, allowing managers to identify above-average sales.

---

## Question 2

Display every order together with the overall average sales.

**Skills Used**

- Scalar Subquery

**Business Insight**

Allows comparison of every sale against the company average.

---

## Question 3

Find customers whose total purchases exceed $2,000.

**Skills Used**

- CTE
- SUM()
- GROUP BY

**Business Insight**

Identifies high-value customers for loyalty programs.

---

## Question 4

Assign row numbers to orders based on sales amount.

**Skills Used**

- ROW_NUMBER()

**Business Insight**

Ranks transactions from highest to lowest.

---

## Question 5

Rank customers by total sales.

**Skills Used**

- RANK()
- Window Functions

**Business Insight**

Shows the highest-value customers.

---

## Question 6

Compare each month's sales with the previous month.

**Skills Used**

- LAG()

**Business Insight**

Makes it easy to identify monthly growth or decline.

---

## Question 7

Calculate the cumulative monthly sales.

**Skills Used**

- SUM() OVER()

**Business Insight**

Shows business growth over time.

---

## Question 8

Calculate cumulative monthly revenue.

**Skills Used**

- Running Total
- Window Functions

---

## Question 9

Rank product categories and calculate their contribution to total revenue.

**Skills Used**

- RANK()
- Percentage Calculation

**Business Insight**

Electronics generated the highest percentage of revenue, contributing 70% of total sales.

---

# Skills Demonstrated

- SQL Programming
- Business Analysis
- Data Analysis
- Window Functions
- Data Aggregation
- Reporting
- Database Querying

---

# Key Findings

- High-value customers were successfully identified.
- Electronics generated the largest share of revenue.
- Monthly revenue trends were analyzed.
- Running totals were calculated.
- Product categories were ranked by revenue contribution.

---

# Recommendations

- Increase inventory for Electronics.
- Reward top customers with loyalty incentives.
- Monitor monthly revenue trends regularly.
- Focus marketing efforts on high-performing product categories.

---
