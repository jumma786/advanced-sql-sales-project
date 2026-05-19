# Advanced SQL Sales Project

## Overview
This project is an end-to-end SQL sales analysis project designed to demonstrate practical database and analytical skills using relational datasets.

The project focuses on analyzing retail business data including customers, products, sales transactions, and city-level information to generate meaningful business insights.

## Objectives
- Analyze sales performance
- Identify top-performing products
- Evaluate customer purchasing behavior
- Generate city-wise sales insights
- Practice real-world SQL querying techniques

## Dataset Files
The project uses the following datasets:

- `sales.csv`
- `customers.csv`
- `products.csv`
- `city.csv`

## Project Structure
```text
advanced-sql-sales-project/
│
├── data/
│   ├── sales.csv
│   ├── customers.csv
│   ├── products.csv
│   └── city.csv
│
├── sql/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   ├── analysis_queries.sql
│   └── advanced_queries.sql
│
└── README.md
```

## SQL Concepts Used
This project demonstrates:

- SELECT statements
- WHERE clauses
- GROUP BY
- ORDER BY
- Aggregate functions
- INNER JOIN
- LEFT JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- Ranking functions

## Example Business Questions Solved

### Sales Analysis
- What is the total sales revenue?
- Which products generated the highest sales?

### Customer Analysis
- Which customers spent the most money?
- Which city has the highest number of customers?

### Product Analysis
- What are the top-selling products?
- Which product categories perform best?

### Advanced SQL Analysis
- Ranking products based on sales
- Using CTEs for complex business reporting
- Performing multi-table joins for insights

## Sample SQL Query

```sql
SELECT 
    p.product_name,
    SUM(s.sales_amount) AS total_sales
FROM sales s
JOIN products p
ON s.product_id = p.product_id
GROUP BY p.product_name
ORDER BY total_sales DESC;
```

## Tools Used
- SQL Server Management Studio (SSMS)
- GitHub

## Skills Demonstrated
- Relational database management
- SQL query writing
- Data analysis
- Business intelligence reporting
- Analytical thinking
- Data aggregation and reporting

## Learning Outcomes
Through this project, I improved my understanding of:

- Database design
- SQL joins and relationships
- Real-world sales analysis
- Writing advanced SQL queries
- Data-driven business insights

## Author
Jumma Mohammad
