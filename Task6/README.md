## 📊 Sales Trend Analysis Using MySQL

## 📌 Task 6 – SQL Aggregation Analysis

## 🎯 Objective

The objective of this task is to analyze monthly sales trends by calculating:

 -Monthly Revenue

 -Monthly Order Volume

This analysis helps in understanding business performance over time.

## 🗂 Dataset Details

Database: online_sales

Table: orders

## Columns Used

| Column Name  | Description                      |
| ------------ | -------------------------------- |
| `order_id`   | Unique identifier for each order |
| `order_date` | Date when the order was placed   |
| `amount`     | Revenue generated from the order |
| `product_id` | Identifier of the product sold   |


## 🛠 Tools Used

MySQL

MySQL Command Line / Workbench

## 🧠 SQL Concepts Applied

-YEAR() – Extract year from date

-MONTH() – Extract month from date

-SUM() – Calculate total revenue

-COUNT(DISTINCT) – Calculate total orders

-GROUP BY – Aggregate monthly data

-ORDER BY – Sort results chronologically

-WHERE – Filter specific year

## 📈 Key Insights

-March recorded the highest revenue (1200.00).

-February recorded the lowest revenue (450.00).

-Order volume remained constant across months.

-Revenue fluctuations are driven by product pricing.

-Monthly aggregation helps identify performance trends.

## 🧠 Conclusion

-This project demonstrates how SQL aggregation functions can be used to analyze time-based business trends.

-Monthly revenue and order analysis provide valuable insights for strategic planning and performance monitoring.
