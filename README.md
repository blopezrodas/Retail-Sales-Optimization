# Retail Sales Optimization Dashboard – Executive Insights for Strategic Growth

### Link : https://app.powerbi.com/links/poM0pNgcVy?ctid=e85c5307-76b1-4c48-bc5d-e88373dda261&pbi_source=linkShare&bookmarkGuid=904306d6-4cda-4247-b63b-87c6a78251d7


## Overview/Problem Statement
Superstore is a fictional national retail company. I was hired as a Data Analyst to optimize sales performance. My task was to identify actionable insights into revenue drivers, regional opportunities, product trends, and customer segments. Using a real-world sales dataset, I performed end-to-end analysis — from data cleaning in Python to delivering a fully interactive Power BI dashboard.


## Business Questions:
#### Executive Summary
- How is the business performing in terms of sales and profit?
- Are sales and profits increasing or declining month-over-month (MoM) and year-over-year (YoY)?
- How is the business performing this period compared to previous periods?

#### Regional Analysis
- Which regions, states, and cities generate the most revenue and profit?
- Are there regions/states/cities with high sales but low profitability?
- Where should we focus sales efforts or cost optimization?

#### Product Performance
- Which product categories and sub-categories contribute most revenue and profit?
- Are there low-margin or underperforming products?
- What are the trends in product demand?

#### Customer Segment Analysis
- Who are our most valuable customers?
- How often do customers purchase, and how much do they typically spend?
- What is the average customer’s lifetime value (CLTV)?
- Which customers are at risk of churning?


## Data
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). It consists of 9993 sales transactions from January 2014 to December 2017. It includes detailed information on orders, products, customers, shipping, and regions, with key variables such as order date, sales, profit, quantity, discount, product category, customer segment, and geographic location.

## Data Cleaning
The raw Superstore dataset was cleaned and prepared using Python in a Jupyter notebook. This involved correcting data types (especially for date fields), standardizing categorical entries, and removing duplicates. The cleaned dataset was then exported as a CSV and imported into Power BI, where additional features such as order month/year, profit margin, and customer-level aggregations were created to support deeper analysis and visualization. The cleaned dataset "SuperStore_cleaned.csv" is available in my Github repository.

## Executive Summary
![Image](https://github.com/user-attachments/assets/34337dcd-d081-47b3-be4c-fcc1ff4f4be4)

#### KPIs
#### Total Sales by Region
#### Total Sales by Segment
#### Total Profit by Region
#### Total Profit by Segment
#### Sales Trends
#### Profit Margin Trends

## Regional Insights
![Image](https://github.com/user-attachments/assets/e7f54d80-c81a-4bf5-adbc-60b4fe435f7a)

#### Total Sales by Region
#### Profit Margin % by Region
#### Total Sales by Region over Time
#### Total Sales by State
#### Top 15 Cities by Total Sales

## Product Performance
![Image](https://github.com/user-attachments/assets/cc94fe44-82ea-41a2-88ea-95ab40cafde8)

#### KPIs
#### Total Sales Category
#### Total and Cumulative Sales by Product
#### Sales Trend of Top 20% Products over Time
#### Top 10 Products by Revenue

## Customer Segment Analysis
![Image](https://github.com/user-attachments/assets/a653c42e-61dc-4ae8-aa43-4016055df0e1)

#### KPIs
#### Total Sales by Segments
#### RFM Segments
#### Churn Risk
#### Total Customers by RFM Segment and Churn Risk
#### Top 15 Customers by CLTV

