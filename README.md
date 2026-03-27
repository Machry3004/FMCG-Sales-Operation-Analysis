# FMCG Sales and Operations Dashboard

## Description
This project delivers a comprehensive Power BI dashboard for an FMCG business, transforming raw daily transactional data into actionable insights. The dashboard provides a consolidated view of sales performance, delivery efficiency, promotion effectiveness, and channel/regional performance, enabling data-driven decision-making for management.

## Tools and Tech Stack
- **Power BI** – Data visualization and interactive reporting
- **DAX** – Custom measures and KPIs
- **Power Query** – Data cleaning and transformation
- **Microsoft Excel** – Data validation and exploration

## Problem Statements
The business lacked a single, reliable view of its operations. Management was making critical decisions regarding inventory and marketing spend without a consolidated view of sales, delivery, and promotional data. This project was initiated to centralize these data sources and provide clear, actionable insights.

## Dataset Source Details
- **Source**: `FMCG_2022_2024.csv`
- **Time Period**: 2022 to 2024
- **Scope**: 3 Sales Channels, 3 Regions, multiple SKUs and Brands
- **Records Analyzed**: Over 190,000 daily transactions

## Report Overview
The dashboard consists of two interactive pages covering sales trends, SKU performance, promotion effectiveness, channel and regional revenue, delivery performance, pack type distribution, and brand contribution.

<img src="https://github.com/Machry3004/FMCG-Sales-Operation-Analysis/blob/main/FMCG%201.png">

<img src="https://github.com/Machry3004/FMCG-Sales-Operation-Analysis/blob/main/FMCG%202.png">

*Note: The images above use local file paths. For correct display on GitHub, please upload the images to your repository and update the paths accordingly (e.g., `./images/FMCG1.png`).*

## Business Problems
The dashboard was designed to answer the following 10 key business questions:
1. How are sales trending over time?
2. Which SKUs and brands are driving the most revenue?
3. Are our promotions actually working?
4. Which channel and region is performing best?
5. How reliable is our delivery performance?
6. Which pack types and brands generate the most value?
7. What is the stock turnover rate for key SKUs? *(Identified as a gap)*
8. What is the price sensitivity of our products? *(Identified as a gap)*
9. How is revenue distributed across channels?
10. How does delivery performance vary by channel and region?

## Solution
A two-page interactive Power BI dashboard was developed to answer **8 of the 10 questions** directly. The dashboard features a clean, user-friendly interface with slicers for year, category, channel, and region, allowing non-technical users to explore data independently. It provides a clear view of key metrics, including total revenue, units sold, average delivery time, and promotion effectiveness.

## Methodology
1. **Data Collection**  
   Sourced daily transactional data covering sales, delivery, promotions, pricing, and stock availability.

2. **Data Cleaning and Transformation**  
   Standardized date formats, resolved import errors, and built a calculated `Revenue` column using `Price per Unit × Units Sold` in Power Query.

3. **Analysis and Modeling**  
   Built a structured data model in Power BI. Created DAX measures for KPIs including `Total Revenue`, `Average Delivery Days`, `Total Units Sold`, and `Transaction Count`.

4. **Dashboard Design**  
   Built a two-page interactive report with slicers for Year, Category, Channel, and Region. Designed for non-technical users to explore data without any analytical background.

5. **Insight Generation**  
   Identified patterns in sales seasonality, channel contribution, promotion lift, and delivery consistency. Surfaced actionable gaps for the next reporting cycle.

## Key Findings
- **Balanced Multi-Channel Revenue**  
  Revenue is split almost equally across Retail (33.36%), E-commerce (33.35%), and Discount (33.29%) channels, indicating a healthy multi-channel reach.

- **Top-Performing SKUs**  
  YO-029, YO-005, and YO-012 are the highest revenue-generating SKUs and should be prioritized for stock availability and promotional investment.

- **Promotions Drive Sales**  
  Promotions consistently lift average sales across all featured SKUs, confirming the effectiveness of promotional spend.

- **Consistent Delivery Performance**  
  Average delivery time across all channel-region combinations is a uniform 3 days, indicating a reliable supply chain baseline.

- **Regional Consistency**  
  All three regions (PL-South, PL-North, PL-Central) contribute similarly to revenue, implying low regional concentration risk.

- **Seasonal Sales Trend**  
  Sales peak between May and August and taper off toward the year-end, signaling a clear seasonal curve for inventory planning.

- **Gaps Identified**  
  The dashboard currently lacks analysis for **stock turnover rate** and **price sensitivity**, which are flagged as priorities for the next development phase.

---
**Prepared by:** Manigandan Acharya  
**Completion Date:** March 2026
