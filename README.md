SQL Project on Retail Sales Analysis

 Objective: To analyze retail sales data to gain insights into sales performance, customer behavior, and transaction patterns.

Database Setup
- Database Creation:
  - Created a database named sql_project to store the retail_sales table.
  
- Table Structure:
  - The retail_sales table includes columns for transaction ID, sale date, sale time, customer ID, gender, age, category, quantity, price per unit, cost of goods sold (COGS), and total sale.

Data Cleaning
- Null Value Checks:
  - Queries were executed to identify any records with null values in key columns (e.g., transaction ID, sale date, gender).
  
- Data Deletion:
  - Records containing null values were removed to ensure data integrity for analysis.

Data Exploration
- Sales Overview:
  - Total sales and the number of unique customers were calculated to understand overall performance.
  
- Category Distinction:
  - Distinct categories within the sales data were retrieved for further analysis.

Key Queries and Analysis
- Q.1: Retrieve all transactions for a specific date ('2022-12-06').
  
- Q.2: Filter transactions where the category is 'Clothing' and quantity sold is greater than 4 in November 2022.

- Q.3: Calculate total sales for each category, providing insights into which categories perform best.

- Q.4: Analyze customer demographics by finding the average age of customers in the 'Beauty' category.

- Q.5: Identify transactions with a total sale greater than 1000 to understand high-value sales.

- Q.6: Count transactions by gender within each category to assess demographic engagement.

- Q.7: Calculate average sales per month and identify the best-selling month for each year, revealing trends over time.

- Q.8: Find the top 5 customers based on total sales to identify key customer segments.

- Q.9: Determine the number of unique customers per category, providing insight into customer diversity.

- Q.10: Classify sales into shifts (Morning, Afternoon, Evening) based on sale time to understand peak periods.

Methodology
- SQL Queries:
  - Utilized SQL for data manipulation and analysis.
  - Employed functions like AVG, SUM, COUNT, and GROUP BY for aggregation.
  - Used subqueries and common table expressions (CTEs) to structure complex queries.

 Key Findings
- Sales Performance:
  - Insights from total sales per category and best-selling months help identify areas for marketing focus and inventory management.
  
- Customer Insights:
  - Understanding the demographics of customers who purchase certain categories allows for targeted advertising and product development.

- Operational Insights:
  - Analyzing sales by time shifts helps in workforce planning and optimizing store hours.

- Conclusion

  Project Significance:
   This analysis can help retail managers make data-driven decisions to enhance sales performance and improve customer experience.
