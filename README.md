# Retail-Data-Analysis

SQL queries and Power BI dashboards for data exploration and business analysis.

## Project Overview

This project includes a set of SQL queries and Power BI visualizations used to analyze retail data. It demonstrates how to extract insights from large datasets using database queries and create meaningful dashboards for decision-making support.

## Technologies Used

- SQL (Structured Query Language)
- Microsoft Power BI
- Excel

## Files Included

- `Part3.sql` – Contains multiple SQL queries for analyzing customers, products, and sales behavior.
- `part3.xlsx` – Raw data used for analysis (imported into Power BI).
- `part_3.pbix` – Power BI dashboard showing visualized insights.

## Key Features

- Customer segmentation and ranking based on sales
- Analysis of purchasing behavior
- Identifying top-performing products
- Power BI dashboard with multiple pages and filters
- Usage of joins, aggregations, `RANK()`, `GROUP BY`, and filtering logic

## Example SQL Snippet

```sql
SELECT CustomerID, COUNT(*) AS OrdersCount
FROM Orders
GROUP BY CustomerID
ORDER BY OrdersCount DESC;
```

## How to Use

1. Open `part3.xlsx` to explore the raw data.
2. Use `Part3.sql` to run queries in your preferred SQL environment.
3. Open the `part_3.pbix` file in Power BI to view the interactive dashboard.

## Author

Itay Reznik
