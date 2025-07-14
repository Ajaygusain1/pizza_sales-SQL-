# 🍕 SQL Pizza Sales Analysis Project

A structured SQL project that explores pizza sales data to derive key business insights such as total revenue, customer preferences, peak sales hours, and product performance. This project uses relational modeling, joins, aggregations to demonstrate SQL proficiency.

---

## 📁 Project Overview

This project answers several real-world business questions using structured query language (SQL) on a pizza delivery company’s historical order data.

The analysis includes:
- Revenue trends
- Top-selling pizzas
- Category-wise contribution
- Time-based order patterns
- Pricing insights

---

## 🗃️ Data Schema

The dataset is divided into four CSV files representing normalized relational tables:

| Table Name        | Description                                      |
|-------------------|--------------------------------------------------|
| `orders`          | Order IDs with date and time of purchase         |
| `order_details`   | order_details_id, order_id, pizza_id, quantity |
| `pizzas`          | Pizza ID, type, size, and price information      |
| `pizza_types`     | Name, category, and ingredients of each pizza type |

> All data was imported and structured in a MySQL database. Joins and constraints were handled programmatically.

---

## ⚙️ Tech Stack

- **SQL**: MySQL 8.0
- **Environment**: MySQL Workbench 
- **Data**: CSV format (imported using `LOAD DATA INFILE`)

---

## 📊 Key Questions Addressed

- 1    Retrieve the total number of orders placed.
- 2   Calculate the total revenue generated from pizza sales.
- 3   Identify the highest-priced pizza.
- 4    Identify the most common pizza size ordered.
- 5   List the top 5 most ordered pizza types along with their quantities.
- 6    Join the necessary tables to find the total quantity of each pizza category ordered.
- 7   Determine the distribution of orders by hour of the day.
- 8    Join relevant tables to find the category-wise distribution of pizzas.
- 9   Group the orders by date and calculate the average number of pizzas ordered per day.
- 10    Determine the top 3 most ordered pizza types based on revenue.
- 11    Calculate the percentage contribution of each pizza type to total revenue.
- 12    Analyze the cumulative revenue generated over time.
- 13    Determine the top 3 most ordered pizza types based on revenue for each pizza category.

Each question was solved using optimized SQL queries including `JOIN`, `GROUP BY`, `ORDER BY`,"OVER".

---
## Schema
<img width="1373" height="696" alt="Screenshot 2025-07-13 131319" src="https://github.com/user-attachments/assets/fe772fd1-10d4-4550-b781-f41b032d7bd2" />

---
## Power BI dashboard for pizza sales
<img width="1333" height="741" alt="Screenshot 2025-07-14 220132" src="https://github.com/user-attachments/assets/bf6f839d-950f-433a-8ff9-fa7a04f4de3c" />

**on friday most people like to ordered the pizza**
<img width="1317" height="732" alt="Screenshot 2025-07-14 220316" src="https://github.com/user-attachments/assets/6703485d-4f6c-41ff-8685-c8a27c838b8b" />




