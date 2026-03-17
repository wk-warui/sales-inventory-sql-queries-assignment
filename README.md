# Retail Sales, Customer & Inventory Analytics Dashboard

## Project Overview
This project presents an end-to-end data analytics solution combining SQL and Power BI to analyze retail business performance. It covers customer behavior, product performance, sales trends, and inventory insights.

The goal is to transform raw transactional data into actionable insights through structured queries and interactive dashboards.

## Dataset Description

### Customers
- Customer details and registration data  
- Membership status: Bronze, Silver, Gold  

### Products
- Product information including category, price, and supplier  

### Sales
- Transactional data (sales, quantity, revenue, dates)  

### Inventory
- Stock levels for each product  

## Database Structure
- Schema: assignment
- Relationships:
  - Customers → Sales (customer_id)
  - Products → Sales (product_id)
  - Products → Inventory (product_id)

## SQL Analysis
The project includes 100+ SQL queries covering:

### Basic Queries
- Data retrieval (SELECT)
- Filtering and sorting
- Aggregations (SUM, AVG, COUNT)

### Intermediate Queries
- Joins (INNER, LEFT, RIGHT)
- Grouping and HAVING clauses
- Subqueries

### Advanced SQL
- Common Table Expressions (CTEs)
- Window functions (RANK, NTILE, LAG, LEAD)
- Analytical queries (top customers, product performance)

### Business Questions Answered
- Who are the top customers by revenue?
- Which products generate the most sales?
- What are the best-performing categories?
- Which products are low in stock?
- How do sales trends change over time?

## Power BI Dashboard
Built using Microsoft Power BI, the dashboard provides interactive insights.

### Key Features
- KPI Cards (Total Sales, Customers, Orders, Avg Order Value)
- Sales trend over time (line chart)
- Sales by product and category
- Top customers analysis
- Inventory status monitoring

### Interactivity
- Filters (Slicers):
  - Date
  - Product category
  - Membership status

## Data Visualization Techniques
- Bar charts for product performance  
- Pie charts for category distribution  
- Line charts for trends  
- Tables with conditional formatting for inventory alerts  

## Key Measures (DAX)
- Total Sales  
- Total Quantity Sold  
- Total Customers  
- Average Order Value  

## Tools and Technologies
- SQL (PostgreSQL or relational database)
- Microsoft Power BI (data visualization)
- DAX (Data Analysis Expressions)

## Insights and Outcomes
- Identified high-value customers  
- Highlighted top-selling products  
- Detected low-stock inventory items  
- Analyzed revenue trends over time  

## How to Use
1. Run the SQL script to create and populate the database  
2. Connect Power BI to the database  
3. Load all tables  
4. Create relationships  
5. Build visuals using provided measures  

## Dashboard Preview
<img width="1282" height="725" alt="image" src="https://github.com/user-attachments/assets/4716e4a9-28b5-4a88-b9a0-6ff635b212c1" />


## Future Improvements
- Add forecasting models  
- Include real-time data updates  
- Enhance customer segmentation  
- Integrate machine learning insights  

## Author
Kelvin Warui

## License
This project is for educational and portfolio purposes.
