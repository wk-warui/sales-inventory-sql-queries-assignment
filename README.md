# SQL Queries Assignment – Parts 1 & 2

This repository contains **PostgreSQL queries (1–100)** written for practice and analysis on a sample database with `Customers`, `Products`, `Sales`, and `Inventory` tables.  
The queries range from **basic retrieval** to **advanced analytics** using subqueries, CTEs, and window functions.

## Database Tables

### Customers

customer_id, first_name, last_name, email, phone_number, registration_date, membership_status


### Products


product_id, product_name, category, price, supplier, stock_quantity


### Sales


sale_id, customer_id, product_id, quantity_sold, sale_date, total_amount


### Inventory


product_id, stock_quantity

## Query Categories

### Part 1 (Queries 1–50)

**Basic Queries**
- Select all data, count products, filter by price or category  
- Find min/max prices and total sales per product  

**Aggregations & Joins**
- Total quantity sold per product  
- Total amount spent per customer  
- Concatenate names  
- Self-joins to find customers with the same membership  
- Products with low stock or high sales  

**Joins & Filters**
- Customers by product category  
- Top customers by sales  
- Most expensive product sold  
- Average quantity sold per product  
- Total sales in specific months  

**Advanced Analytics**
- Customers buying within registration periods  
- Price range filtering  
- Most frequent customers  
- Products with remaining stock  
- Products with specific keywords (like 'Phone')  

**Expert Level**
- Total sales by membership or category  
- Monthly and yearly aggregation  
- Products not sold in the last 6 months  
- Top 5 customers by purchases  
- Products sold more than a threshold  

### Part 2 (Queries 51–100)

**Subquery Questions**
- Customers who spent above average, never purchased, or purchased more than a specific customer  
- Products priced above average, never sold, or with total sales above average  
- Customers registered earlier than average  

**Common Table Expressions (CTEs)**
- Top spending customers  
- Top-selling products  
- Product category with highest revenue  
- Customers with multiple purchases  
- Products selling above/below average  

**Window Function Questions**
- Ranking customers and products  
- Running totals, previous/next sale amounts  
- Grouping customers into quartiles  
- Ranking within categories  

**Advanced Analytical Questions**
- Customers buying in multiple categories  
- Purchases within registration period  
- Products with stock below average  
- Repeat purchases  
- Top products and categories by revenue  

**Advanced Window + Analytical Problems**
- Top 10% spending customers  
- Products contributing to top revenue  
- Consecutive month purchases  
- Largest stock vs sold difference  
- Spending relative to membership tier  
- Largest single purchase relative to total spending  
- Top 3 most sold products per category  
- Products sold every year in the dataset  

## Best Practices Used

- **Joins:** `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `SELF JOIN`  
- **Aggregates:** `SUM()`, `COUNT()`, `AVG()`, `MAX()`, `MIN()`  
- **Filtering:** `WHERE`, `HAVING`  
- **Window Functions:** `RANK()`, `DENSE_RANK()`, `NTILE()`, `LEAD()`, `LAG()`  
- **Date Functions:** `EXTRACT(YEAR/MONTH)`, `INTERVAL`  
- **String Functions:** `CONCAT()`  
- **Ordering & Limiting:** `ORDER BY`, `LIMIT`  
- **Distinct Values:** `DISTINCT` for uniqueness  

## How to Use

1. Clone the repository:
```
git clone https://github.com/yourusername/sql-analytics.git


Open SQL scripts in your SQL client (DBeaver, pgAdmin, MySQL Workbench, etc.)

Execute queries against your database

Adjust table or column names if needed to match your schema

This collection serves as a reference and practice set for beginner to advanced SQL queries, focusing on analytics, reporting, and business insights.

License

This project is licensed under the MIT License – see the LICENSE file for details.
