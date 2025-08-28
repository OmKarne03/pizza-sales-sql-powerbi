Pizza Sales Analysis – SQL & Power BI
📌 Project Overview
This project analyzes pizza sales data using SQL queries and builds an interactive Power BI dashboard for insights. The goal is to answer important business questions such as:
- How many orders were placed?
- Which pizza generated the highest revenue?
- What time do customers order the most?
- Which pizza categories contribute the most to sales?
🗄️ Database Schema
Tables used in this project:
- orders → order_id, order_date, order_time
- order_details → order_details_id, order_id, pizza_id, quantity
- pizzas → pizza_id, pizza_type_id, size, price
- pizza_types → pizza_type_id, name, category, ingredients
🔑 Key SQL Questions Answered
1. Retrieve the total number of orders placed
2. Identify the highest-priced pizza
3. Count the number of pizzas ordered by size
4. Find top 5 most ordered pizza types
5. Find total pizzas ordered per category
6. Find order count by hour
7. Count number of pizza names per category
8. Find top 5 order days with highest pizza sales
9. Find average pizzas sold per day
10. Calculate revenue by pizza category
11. Calculate percentage contribution of each category to total revenue
12. Analyze cumulative revenue generated over time

👉 All queries are available in SQL/pizza_queries.sql
👉 Explained with screenshots in SQL_Queries.md


📌 Tools & Technologies
- SQL (MySQL )
- Power BI
- GitHub for version control
📢 Future Improvements
- Add advanced KPIs (Customer retention, repeat orders)
- Automate daily refresh of Power BI dashboard
- Build web-based interactive dashboard
