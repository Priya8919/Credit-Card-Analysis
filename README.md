Credit Card Financial Dashboard (Power BI)
📘 Overview

This Power BI project analyzes credit card customer financial data to uncover insights into spending behavior, payment patterns, credit utilization, and customer risk segmentation.

The dashboard empowers stakeholders to:

Monitor credit utilization and outstanding balances

Identify high-risk customers

Track late fees and total income

Understand customer demographics (age, income, and region)

Evaluate acquisition costs and satisfaction levels

🧾 Dataset

File Used: credit_card.csv
Dashboard File: credit card.pbix
Data Preparation Steps

Data Cleaning

Removed duplicates and null values

Standardized column names

Converted date fields to correct data types

Feature Engineering

Derived new metrics using DAX:

Outstanding Balance

Late Fees

Customer Satisfaction Score

Customer Acquisition Cost (CAC)

Total Income

Grouping

Age Groups: Under 25, 25–34, 35–44, 45–54, 55–64, 65+

Income Groups: Low, Medium, High

CAC Groups: Low CAC, Medium CAC, High CAC
🧭 Dashboard Features
📍 Main Sections

Customer Overview

Total Customers

Gender & Age Distribution

Income Group Breakdown

Spending & Utilization Analysis

Average Credit Utilization

Spending by Category

Outstanding Balances

Payment & Late Fee Insights

On-Time vs Late Payments

Total Late Fees Collected

Revenue Insights

Interest Income

Late Fees

Merchant Fee Revenue

Customer Acquisition Metrics

CAC by Channel or Month

CAC Groups (Low, Medium, High)

Satisfaction & Risk Segmentation

Customer Satisfaction Score

Credit Risk Tier Analysis

🎨 Visualizations

KPI Cards: Total Income, Average Utilization, CAC, Satisfaction Score

Donut Charts: Age Group, Income Group, CAC Group Distribution

Bar/Column Charts: Spending by Category, Late Fee by Age/Income Group

Line Charts: Monthly CAC Trends, Outstanding Balance Growth

Heatmap / Matrix: Cross-tab between Income & Age Groups

Gauge: Overall Satisfaction Score
🚀 Tools Used

Power BI Desktop — Dashboard creation and DAX modeling

Microsoft Excel / CSV — Data source

DAX — Custom measures and KPIs

Power Query — Data cleaning and transformation

📚 Insights & Recommendations

High Utilization Customers (≥80%) have greater credit risk and higher late fees.

Medium Income Group shows the best payment consistency.

CAC Reduction possible by optimizing campaigns in regions with higher customer yield.

Customer Satisfaction directly correlates with on-time payments and lower utilization.
