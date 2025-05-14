# 🍕 Pizza Sales Analysis using SQL
This project demonstrates the use of SQL to analyze a large pizza sales dataset. The analysis was conducted by importing CSV files from a pizza_sales.zip archive into a relational database. The goal was to derive actionable insights from the data such as sales performance, order trends, and customer preferences.

# 📁 Dataset Overview
The dataset includes the following key tables:

orders: Contains information about order ID, date, and time.
order_details: Tracks the quantity and types of pizzas ordered.
pizzas: Holds data on pizza sizes, prices, and associated types.
pizza_types: Describes the name and category of each pizza type.

# 🛠️ Key Operations
Created a MySQL database (pizza_hut) to store imported data.
Defined tables optimized for handling large datasets (>10K entries).
Performed SQL joins and aggregations to combine and analyze data across tables.

# 📊 Analysis Highlights
Total Orders: Counted the total number of orders placed.
Revenue Calculation: Computed total revenue from pizza sales.

Top Performers:
Most expensive pizza
Most commonly ordered pizza size
Top 5 most ordered pizza types
Top 3 revenue-generating pizza types

Order Patterns:
Hourly distribution of orders
Daily average pizzas ordered
Category-wise pizza distribution and quantity sold

# 📌 SQL Concepts Used
Table creation and primary keys
Aggregations
Joins
Grouping and ordering results
Subqueries and date/time functions
