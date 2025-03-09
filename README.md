# Food Story Sales Performance

## 📌 Overview

Food story is one of the cloud kitchen platforms in Indonesia with branches spread throughout Indonesia, especially in Jakarta. We were assigned to analyze their data, especially sales data in various regions in Indonesia and provide the best insights to help the management team make informed decisions regarding the future of Food Story to improve their sales performance.

## 📊 Data Collection

The dataset is provided in a .csv (comma separated value) and contains various details about each customer data, sales report including branch level, detailed menu, customer level. 

## 🔍 Key Data Fields

1. Customer data: customer data such as order ID, sales type, sales number, full name, email and phone number
   
Sales report include 3 tables, including:
1. Branch level: contains data on various branches, including bill total and grand total
2. Detailed Menu: menu items sold at Food Story
3. Customer level: sales from customers

## 🛠️ Data Processing

There are 3 stages of data processing:

1. Data formatting: we have date data in different formats such as "DD/MM/YYYY", "MM/DD/YYYY" or "YYYY/MM/DD".

In the formatting stage, we convert the date data into a format like this: "DD/MM/YYYY"
   
2. Handling Missing Value: in the customer_name column, we have data on the name of customers who shop at Food Story, but the column has a lot of 'unknow' data.

This needs to be considered whether it should be removed or left alone. We can remove duplicates as long as the data is indeed worth removing so that is facilities the next analysis process.

3. Handling Outliers: we have a dataset about the revenue from product sales in this company. If there area revenues that are much lower or much higher than others, then this can be an outlier.

However, it needs to be considered whether to delete this outlier if it is considered incorrect data or can be retained if it has a valid reason such as the total bill of sales.

## 📈 Exploratory Data Analysis (EDA)

We analyze the data using Power BI for cleansing and visualization data. 

1. Customer dataset
- Analyze the total sales by customer name
- Analyze total orders and total users with details based on sales type

2. Sales Report (Branch Level)
- Analyze total bill and grand total
- Analyze the busiest time for orders
- Analyze the grand total of branches
- Compare grand total of weekday and weekend

3.  Sales Report (Detailed Menu)
- Analyze the quantity of sold menu
- Analyze the highest revenue from the menu
- Analyze the contribution of each menu based on revenue
- Correlation between cheaper menu price and quantity

4. Sales Report (Customer Level)
- Analyze the order with promotion and no promotion
- Analyze the promotion with high contribution (but excluding no promotion and open bill discount)

## 📌 Conclusion
you can check the conclusion of the analysis in here: (https://medium.com/@ciaamoons/food-story-sales-performance-data-analysis-group-project-using-power-bi-bf25e9525be5)

📍 This analysis is part of a group project conducted during our bootcamp.
