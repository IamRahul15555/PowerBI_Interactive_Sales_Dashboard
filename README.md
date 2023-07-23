# Business Success through Data Analysis - Sales Data

## Overview

This Power BI project aims to contribute to the success of a business by utilizing data analysis techniques on their sales data. The dataset comprises two years of sales data (2019 and 2020), including customer orders, customer details, order details, and regional information.

## Dataset Overview

The dataset includes the following information:

- Sales data for the years 2019 and 2020
- Customer orders and order details
- Customer information
- Regional details

## Data Import and Cleaning

The data was imported from a CSV file into Power BI. To ensure data quality, the dataset underwent a thorough cleaning process. The data cleaning steps involved:

- Transforming the dataset using Power Query Editor
- Changing data types to appropriate formats
- Removing empty columns
- Replacing inconsistent values
- Using the first row as headers for the dataset

## Dashboard Creation

The cleaned data was loaded into the Report view, and the process of creating the dashboard began. The dashboard includes various key performance indicators (KPIs) based on the dataset, providing valuable insights into the business's performance. The following KPIs were showcased:

1. Sum of Sales by Category
2. Sum of Sales by Payment Mode
3. Sales by Ship Mode
4. Sales by Category
5. Monthly Sales and Profit for both years
6. Sum of Sales and Profit by Region (Central, East, South, West)

Additionally, cards were added to the dashboard to display important KPIs, such as Total Orders, Sales, Profit, and Average Ship Days. To calculate Average Ship Days, a new data field was created using DAX queries with the DATEDIF function, which determined the time taken to ship a product. The average time taken was then displayed as a KPI.

## Insights

The analysis of the sales data provided the following insights:

- Payment Mode: Most customers prefer Cash on Delivery (COD) as their payment mode.
- Region: The highest sales are recorded in the West region.
- Average Ship Days: The average time taken to ship a product is 4 days.

## Conclusion

Through data analysis, this Power BI project offers valuable insights to help the business improve its performance, optimize operations, and drive success. By leveraging the power of data-driven decision-making, the business can make informed strategies for future growth and profitability.
