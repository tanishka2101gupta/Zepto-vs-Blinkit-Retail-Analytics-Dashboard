# Zepto vs Blinkit: SQL Business Analysis 🧠📊

This project provides a SQL-based business analysis comparing two leading Indian quick-commerce platforms — **Zepto** and **Blinkit**.

The project answers **13 business questions** using SQL queries, reusable views, aggregations, joins, and window functions. Key findings are presented through a **PowerPoint presentation** for better business understanding.

---

## 📁 Project Structure

* `views_script.sql` → SQL views created for different business questions
* `raw_queries.sql` → Raw SQL queries without using views
* `Zepto_vs_Blinkit_SQL_Project_Adhish.pptx` → Final presentation with insights
* `README.md` → Project documentation

---

## 📊 Dataset Overview

The dataset consists of three manually created and Excel-cleaned tables:

| Table       | Description                                                         |
| ----------- | ------------------------------------------------------------------- |
| `customers` | Customer details such as name, age, gender, email, city, and state  |
| `products`  | Product name, brand, category, and price                            |
| `orders`    | Order date, time, total bill, quantity, product ID, and customer ID |

---

## 🔍 Business Questions

The analysis focuses on the following questions:

1. Who are the top 5 customers by total spending?
2. Which age group and brand generate the highest revenue?
3. What are the most ordered product categories for each brand?
4. How is revenue distributed across different age groups?
5. What are the top 3 selling products for each brand?
6. Which product categories are exclusive to Zepto?
7. How does yearly revenue compare between Zepto and Blinkit?
8. Which are the top 3 cities based on order volume?
9. Which are the bottom 3 states based on revenue?
10. What are the monthly and yearly revenue trends?
11. How do weekend sales compare between the two brands?
12. Which customers placed more than 2 orders for each brand?
13. What is the total number of repeat orders by brand?

---

## ⚙️ Technologies Used

* **Excel** – Data cleaning and quantity generation
* **MySQL** – Data analysis and business queries
* **PowerPoint** – Business insights and presentation
* **Power BI** – Dashboard-level visualization

---

## 🧠 SQL Concepts Used

* `JOIN` – Combining data from multiple tables
* `GROUP BY` – Aggregating business data
* `ORDER BY` – Sorting results
* `HAVING` – Filtering aggregated results
* `CASE WHEN` – Creating age-group segments
* `RANK()` – Ranking products and customers
* **Window Functions** – Advanced analytical calculations
* **Views** – Creating reusable SQL logic

---

## 📌 Key Insights

Some of the major insights identified from the analysis include:

* 🔹 Zepto shows stronger sales performance in Tier-1 cities.
* 🔹 Blinkit performs strongly in weekend orders among younger customers.
* 🔹 **Beverages and Snacks** are among the most frequently ordered categories.
* 🔹 Repeat customers contribute significantly to overall revenue.

---

## 📥 How to Use

1. Import the `customers`, `products`, and `orders` CSV files into MySQL.
2. Run `views_script.sql` to create the required views.
3. Execute the queries from `raw_queries.sql` or use:

   ```sql
   SELECT * FROM view_name;
   ```
4. Open the PowerPoint presentation to explore the key business insights.

---

## 👤 Project Author

**Tanishka Gupta**

📧 Email: [tanishkagupta00@gmail.com](mailto:tanishkagupta00@gmail.com)
🔗 LinkedIn: [www.linkedin.com/in/tanishkagupta21]

**Skills & Tools:** Python, SQL, Excel, Power BI, MySQL

---


