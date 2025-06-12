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

This page analyzes customer segments to identify high-value buyers, purchasing patterns, and churn risk, enabling targeted retention and growth strategies.

The RFM segments are defined as:
- New customer: Customers just started, likely no clear patterns yet.
- Champions: High frequency, recent activity, and high value = your best customers.
- Loyal: Consistent purchasers even if not highest spenders or recent.
- Low Value: Low monetary contribution, might need nurturing or upselling.
- Regular: Everyone else

The Churn Risk segments are defined as:
- New customer: Customers just started, likely no clear patterns yet.
- Active: Customers who have made a recent purchase.
- At Risk: Customers who haven't purchased in a while.
- Churched: Customers who haven't purchased in such a long time that they are considred "long gone".

#### Business Questions Answered
- Who are our most valuable customers?

  The RFM analysis categorizes 31 customers as "Champions" and 128 customers as "Loyal".
  The top 15 customers, identified using Customer Lifetime Value (CLTV), contribute a significant share of revenue and profit. Notably, the top 15 of customers drive ~10% of total sales, emphasizing the importance of retention strategies for this group. Among these customers, only 4 are classified as Champions and 2 as Loyal, while the majority (9) fall into the Regular RFM segment — suggesting that high monetary value can exist even outside traditionally loyal segments. Despite high sales contributions, 2 of these top customers operate at a loss (with profit margins of -7.91% and -14.08%), highlighting the importance of balancing acquisition with profitability. Profit margins across this group vary widely — from as low as -14.08% to as high as 47.14% — suggesting that CLTV alone does not guarantee profitability and should be analyzed alongside margin data.

- How often do customers purchase, and how much do they typically spend?

  Across all customers, the average order valua is $459, the average purchase frequency is 6 orders per year, and the average customer lifespan is 2.7 years.

- What is the average customer’s lifetime value (CLTV)?

  CLTV = Avg Order Value × Frequency (Annual) × Lifespan (years)
  
  The average customer's lifetime value is $7,835.

- Which customers are at risk of churning?

  The Churn Risk analysis categorizes 436 customers as "Active", 258 customers as "At Risk", and 99 as "Churched".
  Among the top 15 customers by CLTV, 5 are at risk, and 1 has already churned, highlighting the urgency of targeted retention efforts to protect high-value relationships and prevent potential revenue loss.

