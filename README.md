## TASK 6 Elevate Labs 
- This task analyzes monthly sales trends using SQL on the OnlineSalesData dataset.
- The main objective is to understand business performance by calculating total revenue and number of orders per month.
- The analysis was performed using SQLite and SQL aggregation techniques.
- The date column was used to extract year and month using the strftime() function.
- Total revenue for each month was calculated using SUM(total_revenue).
- Order volume was determined using COUNT(DISTINCT transaction_id).
- The data was grouped using GROUP BY year, month to summarize monthly performance.
- Results were arranged in chronological order using ORDER BY.
- This analysis helps identify sales patterns, monthly performance, and revenue trends over time. 📊
