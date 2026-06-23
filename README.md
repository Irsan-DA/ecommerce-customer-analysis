# E-Commerce Customer Segmentation & Churn Risk Analysis

## Background
In e-commerce, retaining existing customers is significantly more cost-effective than acquiring new ones. Research by Bain & Company indicates that acquiring a new customer can cost 5–7x more than retaining an existing one. Despite this, many businesses lack a systematic way to identify which customers are at risk of churning and which segments deserve more focused retention efforts.

## Problem Statement
This project addresses two interconnected business questions:
1. **Who are our customers?** Segment customers based on purchasing behavior to understand their value and engagement level.
2. **Who is at risk of leaving?** Identify early churn signals to enable proactive retention strategies before customers disengage.

## Objectives
- Perform Exploratory Data Analysis (EDA) to understand data quality and distribution
- Apply RFM (Recency, Frequency, Monetary) analysis to segment customers into meaningful groups
- Identify customers showing early churn signals based on purchasing recency and frequency patterns
- Translate findings into actionable business recommendations

## Dataset
Synthetic e-commerce transaction dataset containing 500 customer records with the following attributes:

| Column | Description |
|--------|-------------|
| user_id | Unique customer identifier |
| age | Customer age |
| gender | Customer gender |
| city | Customer city (Jakarta, Surabaya, Bandung, Medan, Bali) |
| membership | Membership tier (Regular, Silver, Gold) |
| category | Primary product category purchased |
| total_revenue | Total revenue generated per customer |
| num_orders | Total number of orders placed |
| days_since_last_purchase | Days elapsed since last purchase (Recency proxy) |
| rating | Customer satisfaction rating (1–5) |

## Methodology
1. **Data Understanding** — Initial inspection, data types, shape, and statistical summary
2. **Data Cleaning** — Handling missing values, outlier detection, and inconsistency treatment
3. **Exploratory Data Analysis** — Univariate and bivariate analysis across key variables
4. **RFM Segmentation** — Scoring customers on Recency, Frequency, and Monetary dimensions
5. **Churn Risk Identification** — Flagging at-risk customers based on RFM signals
6. **Business Recommendations** — Actionable insights per customer segment

## Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scipy)
- Google Colab
- Microsoft Excel (initial exploration)

## Project Structure
```
ecommerce-customer-analysis/
│
├── data/
│   └── ecommerce_transactions.csv
│
├── notebook/
│   └── ecommerce_eda_rfm_analysis.ipynb
│
└── README.md
```

## Status
🔄 In Progress
