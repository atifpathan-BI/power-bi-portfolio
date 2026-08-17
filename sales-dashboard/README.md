# Retail Sales Performance Dashboard

A 4-page Power BI dashboard analyzing retail sales, product performance, returns, and customer segmentation for a retail business.

## Business Problem
Retail management needed a single view to track overall sales performance, spot underperforming products/categories, understand return patterns, and identify high-value vs at-risk customers — instead of pulling separate reports for each.

## What I Did
- Cleaned and transformed raw sales, product, and customer data using **Power Query**
- Built a star-schema data model connecting Sales, Products, Customers, and Returns tables
- Created **DAX measures** for Total Sales, Net Sales, YoY Growth %, Target Achievement %, Return Rate %, and RFM-based customer segmentation (Champion / Loyal / At Risk / Lost / Potential Loyalist)
- Designed 4 interactive report pages, each with slicers for Date, Region, and Category

## Dashboard Pages

### 1. Executive Summary
High-level KPIs (Total Sales ₹108.45M, Net Sales ₹107.57M, Order Count, Target Achievement 2.21%), monthly sales trend, region-wise sales comparison, and auto-generated key insights.

### 2. Retail Performance
Total Sales vs Sales YTD by month, category-wise sales split (pie chart), and region-wise target achievement table with YoY Growth % of 0.19%.

### 3. Product & Target Analysis
Product-level sales ranking, category-wise sales distribution, and a return-reason breakdown (Defective, Wrong Item, Changed Mind, etc.) with refund amounts and return dates.

### 4. Customer Insights
RFM-based customer segmentation (180 total customers, 55 Champions, 9 At Risk), Recency-Frequency scatter plot, segment distribution donut chart, and customer signup trend over time.

## Key Insights
- Electronics is the top-performing category, driving 33% of total sales
- 55 customers reached Champion tier — the highest-value segment
- Return rate is low at 0.01%, indicating strong product quality
- West region leads regional sales at ₹27.8M
- Year-over-year growth stands at 55.14%, showing strong momentum

## Tools Used
Power BI Desktop · Power Query · DAX · Data Modeling

## Screenshots
![Executive Summary](screenshots/executive-summary.png)
![Retail Performance](screenshots/retail-performance.png)
![Product & Target Analysis](screenshots/product-target-analysis.png)
![Customer Insights](screenshots/customer-insights.png)
