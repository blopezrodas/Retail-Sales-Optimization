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

This page provides a comprehensive view of geographic sales and profitability performance across the U.S., helping identify high-impact regions and underperforming areas.

#### Business Questions Answered
- Which regions, states, and cities generate the most revenue and profit?

  Regions: The West ($0.73M) region generates the most revenue followed by the East ($0.68M) region. Both regions also lead in profit margin.

  States: California ($457,688) generates the most revenue followed by New York ($310,876) and Texas ($170,188).

  Cities: New York City ($256,368), Los Angeles ($175,851), Seattle ($119,541), San Francisco ($112,669) and Philadelphia ($109,077) are the top 5 cities by revenue, while New York City ($62,037), Los Angeles ($30,441), Seattle ($29,156), San Francisco ($17,507) and Detroit ($13,182) are the top 5 cities by profit.

- Are there regions/states/cities with high sales but low profitability?

  Yes. Several high-revenue cities show concerning profit trends.

  Philadelphia is in the top 5 cities in terms of revenue ($109,077), making a large portion of total revenue (4.7%). However, it generates a net loss of $13,838, a -12.69% profit margin. Similarly, Houston, Chicago, and Jacksonville are in the top 15 cities by revenue but generate net losses with profit margins -15.74%, -13.71% and -5.20%, respectively.

- Where should we focus sales efforts or cost optimization?

  **Sales Opportunities**: The West and East regions lead in both revenue and profit margin, indicating strong market performance and continued investment potential. Emerging cities like Seattle and San Francisco offer a solid combination of high revenue and positive profit margins, indicating they are efficient markets worth scaling.

  **Cost Optimization Targets**: Philadelphia ranks in the top 5 cities for revenue, but it operates at a net loss of $13,838 with a -12.69% profit margin, signaling an urgent need for margin improvement or cost reevaluation. Other cities such as Houston, Chicago, and Jacksonville also generate substantial revenue but suffer from double-digit negative profit margins. These should be prioritized for cost audits, pricing strategy reviews and/or operational efficiency improvements.

## Product Performance
![Image](https://github.com/user-attachments/assets/cc94fe44-82ea-41a2-88ea-95ab40cafde8)

This page evaluates product-level sales and profitability to identify bestsellers, underperformers, and opportunities to optimize the product portfolio.

#### Business Questions Answered
- Which product categories and sub-categories contribute most revenue and profit?
  The Canon ImageCLASS 2200 is both the top-selling product by revenue and the most profitable, contributing $61,600 in sales and $25,200 in profit.
  The top category is technology by revenue ($0.84M) and profit ($0.15M) — reinforcing the need to maintain a strong tech product lineup.

- Are there low-margin or underperforming products?
  The table of top 10 products by revenue reveals that tec-ma-10002412, off-bi-10004995, and off-su-10000151 have net losses with profit margins -8.0%, -10.45% and -1.54%, respectively. Additionallu, fur-ch-10002024 breaks even with a profit margin of 0%. These products may warrant pricing reviews or cost optimization, as they contribute to revenue but undercut profitability.
  
- What are the trends in product demand?
  A Pareto analysis shows that the top 20% of products generate over 77.4% of total revenue (e.g., ~80%), confirming a classic 80/20 distribution and indicating high sales concentration.
  When tracked over time, these top products exhibit consistent and stable sales over the 4 years, with minor seasonal fluctuations, suggesting predictable demand and strong customer preference for core offerings.

## Customer Segment Analysis
![Image](https://github.com/user-attachments/assets/a653c42e-61dc-4ae8-aa43-4016055df0e1)

#### KPIs
#### Total Sales by Segments
#### RFM Segments
#### Churn Risk
#### Total Customers by RFM Segment and Churn Risk
#### Top 15 Customers by CLTV

