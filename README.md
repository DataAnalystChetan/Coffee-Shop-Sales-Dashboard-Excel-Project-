
# Coffee Shop Sales Dashboard Excel Project


## Problem Statement

Client recently became a franchise owner of a coffee shop chain with three locations in New York City. He does not have any idea of how the shop's operation works and what are current financial status of the shop is.



## Common Questions

• How do sales vary by day of the week and hour of the day?

• Are there any peak times for sales activity?

• What is the total sales revenue for each month?

• How do sales vary across different store locations?

• what is the average price/order per person?

• Which products are the best-selling in terms of revenue?


## The Dataset

https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&page=2&pageSize=10




## Objective

1. Profile and prepare the raw data for analysis

2. Explore the data with Excel PivotTables

3. Build a dynamic dashboard to visualize patterns and trends



## Data Cleaning

1. checked and removed all blank rows from the dataset.

2. Deleted all the duplicated values in the dataset.

3. corrected all the number formats of the columns including the date, currency, and time.


## Data Preparation

1. Extracted and created 4 new columns from the transaction_date column name as follows month, month name, day of week, and day name respectively.

2. created a new column "Hour" from the transaction_time column.

3. Extract the size from the product_details column and create a separate column name size.

4. Removed all the blank spaces in cells using the trim function.

5. created a new column named total bill using the formula transaction_qty * unit_price.

## Pivot Tables

created the pivot table needed for analysis.

## Dashboard

![App Screenshot]([Sales Intractive Dashboard.png)


## The Key Insights

1. the average no. of orders per person is 1.4.

2. the average price/bill per person is $4.69.

3. The total revenue generated by the shop is $698,812.33 over the 6 months.

4. around morning 8 am to 10 am is the peak time for sales.
