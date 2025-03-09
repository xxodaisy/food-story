# **Food Story Sales Performance**

Analysis of Food Story based on group project on out bootcamp

## **Background**

Food story is one of the cloud kitchen platforms in Indonesia with branches spread throughout Indonesia, especially in Jakarta. We were assigned to analyze their data, especially sales data in various regions in Indonesia and provide the best insights to help the management team make informed decisions regarding the future of Food Story to improve their sales performance

## **Data Collection**
The dataset I got was already in .csv (comma separated value)

1. Customer data: customer data such as order ID, sales type, sales number, full name, email and phone number
   
Sales report include 3 tables, including:
1. Branch level: contains data on various branches, including bill total and grand total
2. Detailed Menu: menu items sold at Food Story
3. Customer level: sales from customers

## **Data Preparation**
There are 3 stages of data preparation:
1. Data formatting: we have date data in different formats such as "DD/MM/YYYY", "MM/DD/YYYY" or "YYYY/MM/DD". In the formatting stage, we convert the date data into a format like this: "DD/MM/YYYY"
   
2. Handling Missing Value: in the customer_name column, we have data on the name of customers who shop at Food Story, but the column has a lot of 'unknow' data. This needs to be considered whether it should be removed or left alone. We can remove duplicates as long as the data is indeed worth removing so that is facilities the next analysis process
   
3. Handling Outliers: we have a dataset about the revenue from product sales in this company. if there area revenues that are much lower or much higher than others, then this can be an outlier. However, it needs to be considered whether to delete this outlier if it is considered incorrect data or can be retained if it has a valid reason such as the total bill of sales.

## **Exploratory Data Analysis (EDA)**
We analyze the data using Power BI for cleansing and visualization data. 

1. Customer dataset
   ![image](https://github.com/user-attachments/assets/7599ba3f-d3f9-40d3-89f7-79273007fcba)

2. Branch Level
   ![image](https://github.com/user-attachments/assets/d4b9baa5-d170-4f65-8a12-082b272a2acf)

3. Detailed Menu
  ![image](https://github.com/user-attachments/assets/960ffc41-9592-4fba-b3c0-d004262fec74)

4. Customer Level
   ![image](https://github.com/user-attachments/assets/f7e8a339-303f-4156-babd-a8eaf065a0e1)

## **Conclusion**
you can check the conclusion of the analysis in here: https://medium.com/@nfathiaaa/food-story-sales-performance-data-analysis-group-project-using-power-bi-bf25e9525be5 


