# Pizza-Sales-Analysis-SQL


# Introduction

The project centers around a SQL database schema created to manage and analyze data for a pizza store. 

This schema includes four main tables—order_details, pizzas, orders, and pizza_types—that collectively capture various aspects of the store's operations, from individual orders to the types of pizzas offered. 

The project aims to provide a structured approach to storing and retrieving data, facilitating comprehensive business analysis for better decision-making.


## Tools Used

![icons8-sql-60](https://github.com/user-attachments/assets/490c54d8-b924-4e7d-9ed4-cbce12db7c6a)

![icons8-my-sql-48](https://github.com/user-attachments/assets/7aa37b4b-890f-4039-bf5f-7948bcda1199)


## Methodology

1. Database Schema and Tables:

    Order Details:
    - order_details_id: Unique identifier for each entry.
    - order_id: Links to the orders table.
    - pizza_id: Links to the pizzas table.
    - quantity: Number of pizzas ordered.
    Pizzas:
    - pizza_id: Unique identifier for each pizza.
    - pizza_type_id: Links to the pizza_types table.
    - size: Size of the pizza (small, medium, large).
    - price: Cost of the pizza.
    Orders:
    - order_id: Unique identifier for each order.
    - date: Date of order placement.
    - time: Time of order placement.
    Pizza Types:
    - pizza_type_id: Unique identifier for each type of pizza.
    - name: Name of the pizza type (e.g., Margherita, Pepperoni).
    - category: Categorization (e.g., Vegetarian, Non-Vegetarian).
    - ingredients: List of ingredients.

2. Analysis Objectives:

    - Sales Analysis: Evaluate best-selling pizzas, revenue from different sizes, and pricing effectiveness.
    - Inventory Management: Manage ingredient stocks based on demand patterns.
    - Customer Preferences: Track customer preferences to adjust the menu.
    - Operational Efficiency: Assess peak hours for optimal staffing.
    - Marketing Insights: Support targeted marketing campaigns.






## Insights

    Sales Trends:
    - Identification of best-selling pizzas and revenue generation by size.
    - Monthly and yearly sales performance.

    Inventory Management:
    - Demand patterns for different pizza types and sizes, aiding in stocking decisions.
    - Reduction of waste through efficient inventory planning.

    Customer Preferences:
    - Analysis of customer order trends over time.
    - Data-driven menu adjustments to cater to popular choices.

    Operational Efficiency:
    - Identification of peak order times for better staffing and resource allocation.
    - Improvement in customer service during high-demand periods.

    Marketing Insights:
    - Determination of effective promotions and marketing strategies.
    - Identification of low-sales periods to boost with targeted campaigns.



## Conclusions

- This SQL project serves as both a robust data management system and a strategic business intelligence tool. 
- It provides store managers with actionable insights to enhance customer experience and profitability. 
- By leveraging structured SQL queries, the project demonstrates the practical application of data analysis in a real-world business context, making it a valuable resource for aspiring data analysts and business owners.



