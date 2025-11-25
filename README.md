🛍️ Customer Shopping Behavior Analysis
A Data Analytics Project using Python, SQL, and Power BI
This project analyzes 3,900 customer transactions to uncover trends in shopping behavior, spending patterns, customer segments, and subscription impact. The goal is to simulate real-world data analyst work involving data cleaning, exploratory analysis, SQL querying, and dashboard creation.

📌 Project Objective
To analyze customer shopping behavior and provide data-driven insights that can support marketing, product strategy, and customer retention decisions.

📂 Dataset Overview
Total Rows: 3,900
Total Columns: 18
Key Data Fields:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Information: Item Purchased, Category, Purchase Amount
Behavioral Factors: Frequency of Purchases, Previous Purchases, Review Rating
Transaction Details: Season, Payment Method, Shipping Type, Discount Applied
The dataset also contained 37 missing values in the review_rating column, which were handled during preprocessing. 

🔧 Tools & Technologies Used
Python: Pandas, NumPy, Matplotlib
SQL: MySQL Workbench
Visualization: Power BI
Environment: Jupyter Notebook

🧹 Data Cleaning & Preparation
Performed using Python:
Checked structure using df.info() and summary stats using df.describe().
Imputed missing values in review_rating using category-based median.
Renamed columns into snake_case for consistency.

Created new features:
age_group – Binned customer ages
purchase_frequency_days
Dropped redundant column: promo_code_used.
Loaded cleaned dataset into MySQL Workbench for SQL analysis. 

📊 Key Analytical Questions Answered
Using SQL, the following insights were explored:
Revenue contribution by gender
High-spending customers despite using discounts
Top 5 highest-rated products
Standard vs. Express shipping impact on order value
Subscriber vs. Non-Subscriber spending comparison
Most discount-dependent products
Customer segmentation: New, Returning, Loyal
Top 3 products per category
Repeat buyers' likelihood of subscription
Revenue contribution by age groups 

📈 Key Findings
🔹 Subscription Impact
Subscribers spent slightly less on average ($59.49) compared to non-subscribers ($59.87), but subscribers are more loyal and valuable in the long term. 
🔹 Revenue by Age Group
The Young Adult segment contributed the highest total revenue (~62,143).
Followed by: Middle-aged, Adult, and Senior groups. 
🔹 Shipping Behavior
Customers choosing Express Shipping spent more on average ($60.48) compared to Standard Shipping ($58.46), suggesting premium intent buyers. 
🔹 Top-Rated Products
Top 5 products based on average review rating:
Gloves – 3.86
Sandals – 3.84
Boots – 3.82
Hat – 3.80
Skirt – 3.78

🔹 Top Products by Category
From SQL analysis:
Accessories: Jewelry, Sunglasses, Belt
Clothing: Blouse, Pants, Shirt
Footwear: Sandals, Shoes, Sneakers
Outerwear: Jacket, Coat

📊 Power BI Dashboard
An interactive Power BI dashboard was created displaying:
Revenue by category
Sales by age group
Subscription distribution
Review ratings
Customer counts
This helps stakeholders quickly understand trends through visuals rather than code. 

💡 Business Recommendations
Based on the analysis:
Promote subscription programs with exclusive benefits
Create loyalty rewards for repeat customers
Optimize discount strategies for profit margins
Highlight top-rated products in marketing campaigns
Use targeted advertising for high-revenue age groups and express shipping buyers 

🚀 Why This Project Matters
This project demonstrates my ability to:
✅ Clean and preprocess real-world datasets
✅ Perform SQL-driven business analysis
✅ Build interactive dashboards
✅ Draw actionable business insights
✅ Communicate findings clearly
