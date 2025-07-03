# Olist-Store-Analysis-E-Commerce-Project
Olist Store is an e-commerce platform that connects small and medium-sized businesses (SMBs) in Brazil with customers, operating as a marketplace.

![Olist Store Logo 2](https://github.com/user-attachments/assets/93741254-1e64-4d31-8b9f-a56ff87a1b6b)

## Introduction
This project provides a complete end-to-end data analytics workflow for the Olist Store. The goal is to extract valuable business insights using Excel, SQL, Power BI, and Tableau.

## Project Objectives
- Export, transform, and load the data (ETL).
- Create a data model.
- Identify the key performance indicators/metrics (KPIs).
- Perform the exploratory data analysis (EDA).
- Visualization.

## Project KPIs To Find
- Weekday vs Weekend (order_purchase_timestamp) payment statistics.
- The no. of orders with a review score of 5 and payment type as a credit card.
- The average no. of days taken for order_delivered_customer_date for pet_shop.
- The average price and payment values from customers of Sao Paulo city.
- The relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) vs review scores.

## About The Datasets
The datasets can be found at: Olist Kaggle Dataset

Total 9 datasets:
- Customers: 99,441 rows × 5 columns
- Geolocation: 1,000,163 rows × 5 columns
- Order Items: 112,650 rows × 7 columns
- Order Payments: 103,886 rows × 5 columns
- Order Reviews: 99,224 rows × 7 columns
- Orders: 99,441 rows × 8 columns
- Sellers: 3,095 rows × 4 columns
- Products: 32,951 rows x 9 columns
- Product Category Translation: 71 rows x 2 columns

## Key Fields For Analysis
- Order Lifecycle: From purchase to estimated and actual delivery (order_purchase_timestamp, order_delivered_customer_date, etc).
- Customer Information: Location (city, state, zip_code_prefix).
- Payment Details: Type, installments, value.
- Product And Seller Info: Price, freight, seller location.
- Customer Feedback: Review scores and messages.

## Key Stats
- Order trends over time.
- Payment method distribution.
- Shipping duration and delays.
- Review score distribution.
- Top cities and states by the orders.
- Seller distribution.

## The Process On Different Software
- In Excel: Added more columns, cleaned the datasets off duplicates/blank rows/errors, and merged certain datasets on Power Query.

 ![ETL](https://github.com/user-attachments/assets/3e002db7-1690-4312-b451-a740b049ef34)

- In SQL: Loaded the cleaned datasets from above and written queries to find the project KPIs.

![SQL](https://github.com/user-attachments/assets/37ace18f-e03f-4fe3-a1c9-ef79faee568e) ![SQL 2](https://github.com/user-attachments/assets/b716c295-6997-4d04-a8fd-fea46fabfc4a) ![SQL 3](https://github.com/user-attachments/assets/a9fa1bd9-4859-40fa-9067-ce5cb1e7c30d)

- In Power BI: Done the data modeling between the cleaned datasets, created a bridge table of zip_code_prefix, identified the KPIs, performed the EDA, and made a dashboard.

![Power BI Dashboard](https://github.com/user-attachments/assets/fdea7d3a-d9dc-409e-9586-b599c106805f) ![Power BI Dashboard 2](https://github.com/user-attachments/assets/0b20191d-8214-4ed1-a591-9f7545ba70e4) ![Power BI Dashboard 3](https://github.com/user-attachments/assets/afc29d93-c055-4482-b5ea-e7581568cf19)

- In Tableau: Did the data blending with the cleaned datasets, added certain calculated fields, identified the KPIs, performed the EDA, and made a dashboard.

![Tableau Dashboard](https://github.com/user-attachments/assets/5b24627c-edd8-417a-bb35-cad159eaff2f) ![Tableau Dashboard 2](https://github.com/user-attachments/assets/a7cce214-0494-48c6-aedf-a73573b091a4)

In Short: I used Excel to perform ETL; SQL to find the specified project KPIs; Power BI and Tableau to identify the KPIs, perform the EDA and visualize the data.

## Project KPI Analysis
- People's purchasing and paying rates are higher on weekdays (77%) than on weekends (23%).
- The no. of orders with a review score of 5 and payment type as credit card are 44K-45K which is higher than any review score paired with the payment type and orders.
- The average no. of shipping/delivery days taken to the pet shop is 11-12 days which is a moderate time.
- The average payment value and price from customers of Sao Paulo city is 134:107 which can be interpreted as a positive indicator.
- The average relationship between shipping/delivery days and review scores is 12:4. The average no. of shipping/delivery days has decreased the higher the review score goes in the line chart.

## Other Stats
Other than the KPIs, found the total no. of customers, sellers, products, orders, sales, and profit; the top 5 and bottom 5 products; the top states; the relationship between the payment value and price by year and month through highs and lows; order volumes; order deliveries.

## Conclusion
Hence, this Olist Store Analysis Project provides valuable business insights such as payment statistics, profit margins, distribution patterns, sales trends, delivery timelines, product performance, and customer behavior which help in making strategies such as improving delivery performance, optimizing product categories, enhancing customer experience, tailoring the marketing, leveraging preferred payment methods, and churning the prediction model contributing to more growth.
