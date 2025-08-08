# 📌 Retail_Analysis_SQL_Project
This project focuses on a retail company facing challenges with sales transaction, customer profile and inventory management. Through a comprehensive data analysis approach using SQL, this case study aims to address key business problems and insights such as high and low sales products, segment the customer base, and analyze customer behaviour.

## 📂 Datasets Information

The analysis for this case study is based on the following three datasets:
1.	Sales Transaction: Contains detailed records of sales, including transaction IDs, customer IDs, product IDs, quantity purchased, transaction dates, and prices.
2.	Customer Profiles: Provides information on individual customers, such as customer IDs, age, gender, location, and join dates.
3. Product Inventory: Includes data on the products themselves, such as product IDs, product names, categories, stock levels, and prices.

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
 
1.	JOIN operations for combining relational tables
2.	GROUP BY and HAVING for aggregated insights
3.	SUM, COUNT for total sales, total quantity, customer segments


**Business KPI Modeling:**

Designed queries to track key metrics like:
1.	Total Sales: SUM (quantitypurchased * price)
2.	Total Units Sold: SUM (quantitypurchased)
3.	Number of Transactions: COUNT (*) 
4.	Top products with the highest total sales revenue
5.	Low Sales products 

## 🔍 Key Insights & Solutions

Here are some actionable insights derived from the SQL analysis:
1.	Total Sales: Calculated total sales and quantities sold per product using aggregated queries.
2.	Customer Segmentation: Customers were segmented into "High," "Mid," and "Low" value groups to enable more effective and personalized marketing strategies.
3.	High sales products: ProductID 17 has 9450 total units sold as the highest sale.
4.	Low sales products: ProductID 142 has 27 total units sold as the least sale
5.	Top Customers with recent transactions: Listed each customers with most recent transactions.

## 🧠 Skills Gained

Through this project, I gained hands-on experience in:
1.	Developed practical experience in writing SQL queries to solve real-world business problems.
2.	Learned how to translate key performance indicators (KPIs) into structured database logic.
3.	Strengthened ability to join and manage multiple relational tables effectively.
4.	Built a data-driven, business-oriented problem-solving approach.

## 👤 About Me

 LinkedIn: https://www.linkedin.com/in/dristi-handique/ 





