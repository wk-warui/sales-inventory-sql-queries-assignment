# SQL Queries Assignment Part 1

This repository contains **PostgreSQL queries (1–50)** written for practice on a sample database with **Customers, Products, Sales, and Inventory tables**.  
The queries cover **basic retrieval, aggregation, joins, filtering, grouping, and advanced analytics** scenarios.

## **Database Tables**

1. **Customers**
   - `customer_id`, `first_name`, `last_name`, `email`, `phone_number`, `registration_date`, `membership_status`.

2. **Products**
   - `product_id`, `product_name`, `category`, `price`, `supplier`, `stock_quantity`.

3. **Sales**
   - `sale_id`, `customer_id`, `product_id`, `quantity_sold`, `sale_date`, `total_amount`.

4. **Inventory**
   - `product_id`, `stock_quantity`.

## **Query Categories**

### **Basic Queries**
- Select all data, count products, filter by price or category, find min/max prices, and total sales per product.

### **Aggregations & Joins**
- Total quantity sold per product
- Total amount spent per customer
- Concatenate names
- Self-joins to find customers with the same membership
- Products with low stock or high sales

### **Joins & Filters**
- Customers by product category
- Top customers by sales
- Most expensive product sold
- Average quantity sold per product
- Total sales in specific months

### **Advanced Analytics**
- Customers buying within registration periods
- Price range filtering
- Most frequent customers
- Products with remaining stock
- Products with specific keywords (like 'Phone')

### **Expert Level**
- Total sales by membership or category
- Monthly and yearly aggregation
- Products not sold in the last 6 months
- Top 5 customers by purchases
- Products sold more than a threshold

## **Best Practices Used**
- **JOINs**: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `SELF JOIN`
- **Aggregates**: `SUM()`, `COUNT()`, `AVG()`, `MAX()`, `MIN()`
- **Filtering**: `WHERE`, `HAVING`
- **Date functions**: `EXTRACT(YEAR/MONTH)`, `INTERVAL`
- **String functions**: `CONCAT()`
- **Ordering & Limiting**: `ORDER BY`, `LIMIT`
- **Distinct values**: `DISTINCT` for uniqueness

## **How to Use**
1. Clone the repository.
2. Open SQL scripts in your favorite SQL client (DBeaver, pgAdmin, MySQL Workbench, etc.).
3. Execute queries against your database.
4. Observe results and adjust table/column names if needed to match your schema.

This collection serves as a **reference and practice set** for beginners to advanced SQL queries, including analytics, reporting, and business insights.
