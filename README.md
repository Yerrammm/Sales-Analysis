# Sales Analysis Project | Excel & MySQL

## Project Overview

This project analyzes e-commerce sales data using **Microsoft Excel and MySQL** to identify sales trends, top-performing products, customer behavior, and order status patterns.

The project combines an interactive Excel dashboard with SQL-based analysis to support data-driven business decisions.

## Tools & Technologies

- **Microsoft Excel:** Dashboard creation, PivotTables, slicers, data analysis
- **MySQL:** Data cleaning, querying, joins, aggregations, and business analysis
- **Git & GitHub:** Version control and project documentation

## Dataset Summary

| Metric | Value |
|---|---:|
| Total Customers | 38 |
| Total Products | 20 |
| Total Orders | 120 |
| Order Items | 300 |
| Units Sold | 429 |
| Total Line Sales | 858,424.00 |

*Note: Total line sales includes all order statuses, including cancelled and returned orders.*

## 📊 Excel Dashboard

The interactive dashboard includes sales KPIs, product and category performance, and order analysis. Slicers filter by date, city, category, and order status.

![Sales Dashboard](screenshots/sales_dashboard.png)

[Download the Excel Dashboard](https://github.com/Yerrammm/Sales-Analysis/blob/main/ecommerce_project_excel_sql.xlsx)

## SQL Analysis

SQL queries were used to analyze the following business questions:

1. What are the total sales, units sold, and number of orders?
2. How do sales trends change month by month?
3. Which product categories generate the highest revenue?
4. Which products are the top performers by sales?
5. What are the estimated profit and cost by product?
6. Who are the highest-revenue customers?
7. What is the distribution of delivered, pending, cancelled, and returned orders?
8. Which customers place repeat orders?
9. How does cumulative revenue change over time?
10. What revenue is associated with delivered orders only?

### SQL Concepts Demonstrated

- SELECT, WHERE, ORDER BY, and LIMIT
- Aggregate functions: SUM, COUNT, and ROUND
- GROUP BY and HAVING
- INNER JOIN
- Common Table Expressions (CTEs)
- Window functions
- Revenue and profit calculations
- Data validation

## Key Findings

- **Highest-revenue category:** Electronics — 509,951.00
- **Highest-revenue product:** Monitor 24-inch — 263,974.00
- **Best sales month:** December 2025 — 95,367.00
- **Lowest sales month:** July 2025 — 36,912.00
- **Delivered orders:** 66 out of 120 orders (55%)
- **Cancelled orders:** 18 (15%)
- **Returned orders:** 16 (13.33%)

## Business Recommendations

- Investigate cancellation and return patterns to identify potential operational issues.
- Review Electronics category performance and maintain appropriate inventory for high-demand products.
- Analyze repeat customers to identify opportunities for customer retention.
- Monitor monthly revenue trends to support sales planning.

## Repository Contents

- `sales_analysis.sql` — SQL analysis queries
- `Sales_Dashboard.xlsx` — Excel dashboard workbook
- `screenshots/` — Dashboard screenshots, if included
- `demo/` — Dashboard demonstration video, if included

*Filenames may differ depending on the files uploaded to the repository.*

## Assumptions & Limitations

- Sales calculations use the `line_total` field from the dataset.
- The overall sales figure includes all order statuses.
- Profit is estimated as sales minus quantity multiplied by unit cost. It does
