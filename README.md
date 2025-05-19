# Olist-Store-Analysis-E-Commerce-Project
Olist Store is an e-commerce platform that connects small and medium-sized businesses (SMBs) in Brazil with customers, operating as a marketplace.

![Olist Store Logo 2](https://github.com/user-attachments/assets/93741254-1e64-4d31-8b9f-a56ff87a1b6b)

## Introduction
This project provides a complete end-to-end data analytics workflow for the Olist Store. The goal is to extract valuable business insights using Excel, Power BI, Tableau, and SQL.

## Project Objectives
- Export, transform, and load the data (ETL).
- Perform exploratory data analysis (EDA).
- Identify the key performance indicators/metrics (KPIs).
- Visualization.

## Project KPIs To Find
- Weekday vs Weekend (order_purchase_timestamp) payment statistics.
- The no. of orders with a review score of 5 and payment type as a credit card.
- The average no. of days taken for order_delivered_customer_date for pet_shop.
- The average price and payment values from customers of Sao Paulo city.
- The relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) vs review scores.

## About The Datasets
The datasets can be found at: Olist Kaggle Dataset

It includes 9 datasets:
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
- In Excel: Cleaned the datasets off duplicates/blank rows/discrepancies, merged certain datasets, and added more columns on Power Query.

![ETL](https://github.com/user-attachments/assets/b8bc840c-eaa2-460a-bdbf-1cdb623ead81) 

- In SQL: Loaded the cleaned datasets from above and written queries to find the project KPIs.

![SQL](https://github.com/user-attachments/assets/37ace18f-e03f-4fe3-a1c9-ef79faee568e) ![SQL 2](https://github.com/user-attachments/assets/b716c295-6997-4d04-a8fd-fea46fabfc4a) ![SQL 3](https://github.com/user-attachments/assets/a9fa1bd9-4859-40fa-9067-ce5cb1e7c30d)

- In Power BI: Done the data modeling between the cleaned datasets, created a bridge table of zip_code_prefix, performed the EDA, identified the KPIs, and made a dashboard.

![Power BI Dashboard](https://github.com/user-attachments/assets/eb933e83-646e-4438-aafd-d27c36188a37) ![Power BI Dashboard 2](https://github.com/user-attachments/assets/f0bdf1f3-8290-46f1-888d-03f4216c868a) ![Power BI Dashboard 3](https://github.com/user-attachments/assets/3eb71eef-1a60-4e00-a17d-a2aff5d1b689)

- In Tableau: Did the data blending with the cleaned datasets, added certain calculated fields, performed the EDA, identified the KPIs, and made a dashboard.

![Tableau Dashboard](https://github.com/user-attachments/assets/993cb735-a7a8-4476-806d-a6b7845b648e) ![Tableau Dashboard 2](https://github.com/user-attachments/assets/3c27a369-83a7-4731-8b54-a57a3da1f6e5)

In short, I used Excel to perform ETL, SQL to find the specified project KPIs, Power BI, and Tableau to perform EDA, identify the KPIs, and visualize the data.

## Project KPI Analysis
- People's purchasing and paying rates are higher on weekdays (77%) than on weekends (23%).
- The no. of orders with a review score of 5 and payment type as credit card are 44K-45K which is higher than any review score paired with the payment type orders.
- The average no. of shipping/delivery days taken to the pet shop is 11-12 days which is a moderate time.
- The average payment value and price from customers of Sao Paulo city is 134:107 which can be interpreted as a positive indicator.
- The average relationship between shipping/delivery days and review scores is 12:4. The average no. of shipping/delivery days has decreased the higher the review score goes in the line chart.

## Overall Stats Analysis
Other than the KPIs, found the total no. of customers, sellers, products, orders, sales, and profit; the top 5 and bottom 5 products; the top states; the relationship between the payment value and price by year and month through highs and lows; order volumes (positive/increased); order deliveries (positive/increased).

## Conclusion
Hence, this Olist Store Analysis Project provides valuable business insights such as payment statistics, profit margins, distribution patterns, sales trends, delivery timelines, and customer behavior which help in making strategies such as improving delivery performance, optimizing product categories, enhancing customer experience, tailoring the marketing, leveraging preferred payment methods, and churning the prediction model contributing to more growth.
