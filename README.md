E-Commerce Sales & Customer Analysis (SQL Project)

📌 Project Overview

This project focuses on analyzing e-commerce sales and customer data using MySQL. The goal is to extract meaningful business insights such as sales trends, top customers, and product performance using SQL queries and relational database concepts.

The dataset contains 500+ records across multiple tables including customers, products, orders, and order items.

🎯 Project Objectives

Analyze sales performance and revenue trends

Identify top customers and repeat buyers

Evaluate product category performance

Understand customer purchasing behavior

🗄️ Database Schema

The database consists of 4 tables:

1️⃣ Customers
Column	Description
customer_id	Unique customer ID
customer_name	Customer name
city	Customer location
signup_date	Customer registration date
2️⃣ Products
Column	Description
product_id	Unique product ID
product_name	Product name
category	Product category
price	Product price
3️⃣ Orders
Column	Description
order_id	Unique order ID
customer_id	Customer reference
order_date	Order date
total_amount	Total order value
4️⃣ Order_Items
Column	Description
order_item_id	Unique item ID
order_id	Order reference
product_id	Product reference
quantity	Quantity purchased
🔑 SQL Concepts Used

This project demonstrates the use of:

SELECT statements

JOIN operations

GROUP BY and HAVING

Aggregate functions (SUM, COUNT, AVG)

Subqueries

Common Table Expressions (CTE)

CASE statements

Window Functions (RANK)
