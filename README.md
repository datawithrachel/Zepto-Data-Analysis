### Zepto SQL Data Analysis



This project performs data exploration, cleaning, and analysis on the Zepto dataset to extract meaningful business insights. The focus is on identifying best-value products, category-wise revenue, discount patterns, and inventory weight distribution.



###### 📌 Introduction



The Zepto Data Analysis project analyzes product-level data such as MRP, discounts, stock availability, and weight to answer key business questions. The objective is to help in:

\- Identifying high-value products for customers.

\- Understanding category-level performance.

\- Optimizing inventory and revenue management.



Through SQL queries, the project provides actionable insights that can guide decision-making in pricing strategies, stock management, and promotional offers.



###### 🎯 Objectives



The main objectives of this project are:



1\. Top 10 Best-Value Products – Find products with the highest discount percentage.

2\. High-MRP Out-of-Stock Products – Identify expensive products that are currently unavailable.

3\. Estimated Revenue per Category – Calculate expected revenue contribution from each category.

4\. High-MRP, Low-Discount Products – Find products where MRP > ₹500 and discount < 10%.

5\. Top 5 Categories by Average Discount – Discover categories offering the highest discounts on average.

6\. Price per Gram Analysis – Compute price per gram for products above 100g to assess best value.

7\. Product Categorization by Weight – Classify products into Low, Medium, and Bulk categories.

8\. Total Inventory Weight per Category – Calculate inventory weight distribution across categories.



###### 🗂️ Project Structure



📦 Zepto-Data-Analysis

 ┣ 📦 zepto\_dataset        # Raw data

 ┣ 📜 zepto\_data\_analysis.sql        # SQL script containing data exploration, cleaning, and analysis queries

 ┣ 📜 problem\_statement.pdf        # Questions/Objective

 ┣ 📜 README.md    # Project documentation



###### 📦Dataset



The dataset includes the following fields:



\- sku\_id – Unique identifier for each product

\- category – Product category

\- name – Product name

\- mrp – Maximum Retail Price

\- discountPercent – Discount percentage on the product

\- availableQuantity – Available stock quantity

\- discountedSellingPrice – Selling price after discount

\- weightInGms – Product weight in grams

\- outOfStock – Availability status (true/false)

\- quantity – Pack size or quantity



###### 🔍 Data Exploration \& Cleaning



The dataset was first explored and cleaned before analysis:

\- Checked row counts, null values, and duplicates.

\- Identified distinct categories and stock distribution.

\- Removed products with zero MRP.

\- Converted values from paise to rupees for consistency.

###### 

###### 📊 SQL Analysis



The zepto\_data\_analysis.sql file includes all queries that address the objectives, including:

\- Discount-based product ranking

\- Revenue calculations

\- Category-level insights

\- Inventory weight analysis



###### 📝 Notes



* Queries are optimized for PostgreSQL but can be adapted to other SQL environments with minor changes.
* This project is for educational and analytical purposes, focusing on SQL problem-solving.
