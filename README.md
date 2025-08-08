# 📌 Retail_Analysis_SQL_Project
This project focuses on a retail company facing challenges with sales transaction, customer profile and inventory management. Through a comprehensive data analysis approach using SQL, this case study aims to address key business problems and insights such as high and low sales products, segment the customer base, and analyze customer behaviour.

## 📂 Datasets Used

The analysis for this case study is based on the following three datasets:
•	Sales Transaction: Contains detailed records of sales, including transaction IDs, customer IDs, product IDs, quantity purchased, transaction dates, and prices.
•	Customer Profiles: Provides information on individual customers, such as customer IDs, age, gender, location, and join dates.
•	Product Inventory: Includes data on the products themselves, such as product IDs, product names, categories, stock levels, and prices.

## 🎯 Business Problems Addressed

1.	Operational Efficiency: Optimizing inventory management to ensure efficient stock levels by identifying high and low sales products.
2.	Competitive Advantage: Developing data-driven strategies to stay ahead of competitors by analyzing sales trends and identifying opportunities for targeted offers and promotions.
3.	Customer Satisfaction: Improving customer satisfaction and retention by analyzing customer behavior, including repeat purchases and loyalty, to create more effective and personalized marketing campaigns.

## 🛠️ Methodology

Data Import: All CSV files were imported into MySQL Workbench.

**Tables Used:** 

1. sales_transaction
2. customer_profiles
3. product_inventory

 **SQL Analysis:**
 
•	JOIN operations for combining relational tables
•	GROUP BY and HAVING for aggregated insights like 
•	SUM, COUNT for total sales, total quantity, customer segments


**Business KPI Modeling:**

Designed queries to track key metrics like:
•	Total Sales: SUM (quantitypurchased * price)
•	Total Units Sold: SUM (quantitypurchased)
•	Number of Transactions: COUNT (*) 
•	Top products with the highest total sales revenue
•	Low Sales products 

## 🔍 Key Insights & Solutions

Here are some actionable insights derived from the SQL analysis:
•	Total Sales: Calculated total sales and quantities sold per product using aggregated queries.
•	Customer Segmentation: Customers were segmented into "High," "Mid," and "Low" value groups to enable more effective and personalized marketing strategies.
•	High sales products: ProductID 17 has 9450 total units sold as the highest sale.
•	Low sales products: ProductID 142 has 27 total units sold as the least sale
•	Top Customers with recent transactions: Listed each customers with most recent transactions.

## 🧠 Skills Gained

Through this project, I gained hands-on experience in:
•	Developed practical experience in writing SQL queries to solve real-world business problems.
•	Learned how to translate key performance indicators (KPIs) into structured database logic.
•	Strengthened ability to join and manage multiple relational tables effectively.
•	Built a data-driven, business-oriented problem-solving approach.

## 👤 Contact

•	LinkedIn: https://www.linkedin.com/in/dristi-handique/ 





