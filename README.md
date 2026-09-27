# Customer Behaviour & Segmentation Analysis

**Category:** Data Analysis | **Status:** IN PROGRESS

**Subtitle:** RFM Modeling & Purchase Pattern Analytics

**Technologies:** SQL, Python, Excel

**Skills:** Business Intelligence

## Overview
Applying Recency, Frequency, and Monetary (RFM) segmentation to evaluate customer lifetime value and retention cohorts.

## 01 — Business Problem — Customer Churn & Undifferentiated Marketing
An online retail brand struggled with declining repeat purchase rates. Marketing campaigns were broadcast uniformly to all customers regardless of spending history or purchase recency.

• How can customers be grouped into actionable value segments?
• Which customer segment represents the highest churn risk in Q4?
• What targeted offers yield maximum repeat purchase rate?

## 02 — Dataset & Data Cleaning — Customer Transaction Logs
Extracting transaction history including CustomerID, InvoiceDate, Quantity, UnitPrice, and Country. Cleaning cancelled orders and negative quantities.

• Data cleaning in Python (Pandas) handling missing values and outlier transactions.
• Aggregating customer-level metrics for RFM scoring.

## 03 — RFM Segmentation Methodology — Quantile Scoring & Python Clustering
Calculating Recency (days since last purchase), Frequency (total orders), and Monetary Value (total spend). Assigning 1-5 quantile scores to establish customer tiers (Champions, Loyalists, At-Risk, Lost).

• Python RFM script implementation.
• K-Means clustering validation — [IN PROGRESS].

## 04 — Visualisation & Reporting — Segment Distribution Matrix
Building interactive segment treemaps and retention heatmaps to show customer movement between quarters.

• Visual dashboard graphics — [IN PROGRESS].

## 05 — Preliminary Insights — Cohort Value Disparity
The top 'Champion' tier (top 8% of customers) contributes over 42% of total cumulative revenue.

• Detailed cohort breakdown — [IN PROGRESS].

## 06 — Retention Recommendations — Targeted Campaign Allocation
Formulating segment-specific re-engagement strategies to reactivate 'At-Risk' high-monetary customers.

• Final strategic playbook — [IN PROGRESS].
