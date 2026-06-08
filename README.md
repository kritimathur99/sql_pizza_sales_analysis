# sql_pizza_sales_analysis
# Project Overview

The SQL Pizza Sales Analysis project focuses on extracting meaningful business insights from a transactional pizza sales database using MySQL. The objective of this project is to analyze sales performance, customer ordering behavior, product popularity, and revenue trends by leveraging SQL queries ranging from basic aggregations to advanced analytical techniques.

The dataset consists of four interconnected tables representing orders, order details, pizzas, and pizza types. These tables form a relational database structure that enables comprehensive analysis through table joins and aggregation techniques. By combining data from multiple sources, the project investigates key business metrics that are commonly used in the food and restaurant industry to support operational and strategic decision-making.

The analysis begins with fundamental business questions such as determining the total number of orders placed, calculating total revenue generated, identifying the highest-priced pizza, and discovering the most commonly ordered pizza size. These metrics provide a high-level overview of business performance and customer preferences.

The project then progresses to intermediate-level analyses, including the distribution of orders across different hours of the day, category-wise sales performance, average daily pizza orders, and identifying the highest revenue-generating pizza types. These insights help businesses understand customer demand patterns and optimize inventory, staffing, and promotional strategies.

Advanced analytical queries further explore revenue contribution percentages, cumulative revenue trends over time, and the top-performing pizza types within each category. These analyses provide a deeper understanding of product profitability and sales dynamics, enabling data-driven business decisions.

Throughout the project, various SQL concepts such as JOINs, aggregate functions, grouping, subqueries, Common Table Expressions (CTEs), and window functions are utilized to transform raw transactional data into actionable insights. The project demonstrates how SQL can be effectively used for exploratory data analysis and business intelligence reporting.

Overall, this project showcases the practical application of SQL in solving real-world business problems and highlights the importance of data analysis in understanding customer behavior, improving product offerings, and maximizing revenue in the restaurant industry.


# Dataset Description

The Pizza Sales dataset is a relational database consisting of four interconnected tables that capture transactional information related to pizza orders.

The orders table stores order-level details, including unique order identifiers, order dates, and order times. The order_details table records individual items within each order, including the pizza purchased and the quantity ordered. Together, these tables provide a detailed view of customer purchasing activity.

The pizzas table contains information about different pizza variants, including pizza size and selling price. Each pizza is associated with a pizza type through a unique pizza_type_id. The pizza_types table stores descriptive information such as pizza name, category, and ingredients.

The relationships between these tables enable comprehensive analysis of sales transactions. Orders are linked to order details through order_id, while pizzas are connected to pizza types through pizza_type_id. This relational structure supports advanced querying and business analysis through JOIN operations.

The dataset provides valuable information for analyzing revenue generation, product performance, customer preferences, sales distribution, and operational trends. It serves as an excellent resource for practicing SQL concepts and developing data analytics skills using real-world business scenarios.


# SQL Concepts Used

## Data Retrieval

* SELECT statements
* Filtering and sorting using ORDER BY

## Aggregate Functions

* COUNT()
* SUM()
* AVG()
* ROUND()

## Joins

* INNER JOIN
* Multi-table joins across four tables

## Grouping and Aggregation

* GROUP BY
* HAVING

## Ranking and Top-N Analysis

* ORDER BY with LIMIT
* Revenue-based ranking

## Common Table Expressions (CTEs)

* Used for advanced analytical calculations

## Window Functions

* SUM() OVER()
* PARTITION BY
* Cumulative revenue calculations

## Mathematical Operations

* Revenue calculations using quantity × price
* Percentage contribution calculations

## Date and Time Functions

* Hourly order distribution analysis
* Daily sales trend analysis

# Key Insights

## Customer Ordering Patterns

* Certain pizza sizes are significantly more popular than others.
* Customer demand varies throughout the day, with peak ordering hours generating the highest transaction volumes.

## Revenue Performance

* A small number of pizza types contribute a disproportionately large share of total revenue.
* Premium-priced pizzas generate substantial revenue despite lower order volumes.

## Product Popularity

* Top-selling pizzas consistently outperform others in terms of quantity sold.
* Some pizza categories attract significantly higher customer demand.

## Category Analysis

* Revenue and order quantities differ across pizza categories.
* Category-level performance helps identify the most profitable product segments.

## Sales Trends

* Daily sales analysis reveals fluctuations in customer demand.
* Cumulative revenue trends provide visibility into overall business growth over time.

## Business Intelligence Value

* The analysis identifies top-performing products and categories.
* Insights can support pricing strategies, inventory planning, staffing decisions, and promotional campaigns.

# Conclusion

This SQL Pizza Sales Analysis project demonstrates the use of SQL as a powerful tool for business analytics and decision-making. By analyzing transactional sales data across multiple related tables, the project uncovers valuable insights into customer behavior, product performance, revenue generation, and operational trends.

Through the application of joins, aggregations, Common Table Expressions, and window functions, raw sales data was transformed into actionable business intelligence. The analysis highlights the importance of understanding customer preferences, monitoring sales performance, and identifying high-revenue products to improve business outcomes.

The project not only strengthens practical SQL skills but also showcases the ability to solve real-world business problems using data-driven approaches. The findings generated from this analysis can help restaurant managers optimize product offerings, improve operational efficiency, and maximize revenue growth.




