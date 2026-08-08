# Credit Card Transaction Analytics

An end-to-end data analytics project focused on analyzing customer behaviour, card usage, transaction patterns, and fraud risk.

## Project Overview

The objective of this project is to analyze credit card transactions and identify patterns related to customer spending, card usage, transaction risk, and fraudulent activities.

The project uses four datasets:

| Dataset     | Records |
| ----------- | ------: |
| Customer    |  25,000 |
| Card        |  32,457 |
| Transaction | 250,000 |
| Merchant    |     500 |

## Business Problem

Fraudulent transactions can lead to financial losses, chargebacks, and reduced customer trust. The analysis focuses on identifying fraud hotspots, risky transaction channels, anomalous behaviour, and other factors associated with fraudulent transactions.

## Analysis Performed

* Data Quality Assessment
* Exploratory Data Analysis (EDA)
* Customer Segmentation & Spending Analysis
* Card Portfolio Analysis
* Fraud Detection & Risk Analysis
* Correlation & Relationship Analysis
* Financial & Operational Analysis
* Business Recommendations

## Key Findings

* Fraud accounted for **5.39% of transactions** but represented **25.3% of total transaction value**.
* Average fraud transaction value was approximately **4.7× higher** than the overall average transaction value.
* POS transactions generated approximately **₹797M in fraud losses**.
* Expired, blocked, and lost cards accounted for a significant proportion of fraud incidents.
* Fraud losses showed a noticeable increase between **March and June**.

## Data Quality

The datasets were checked for:

* Missing values
* Duplicate records
* Data types
* Statistical outliers

Date columns were converted from string format to datetime. High-value transactions above ₹1,000,000 were retained because they were associated with fraudulent transactions and were considered valid business observations.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQL
* Power BI
* Excel

## Repository Structure

```text
Credit-Card-Transaction-Analytics/
│
├── README.md
├── EDA/
│   ├── EDA_Notebook.ipynb
│   └── EDA_Report.pdf
│
├── SQL/
│   └── SQL_Analysis.sql
│
├── PowerBI/
│   └── Credit_Card_Analysis.pbix
│
└── Dashboard/
    └── Dashboard_Screenshots/
```

## Business Recommendations

The analysis recommends stronger real-time card-status validation, additional security for high-risk channels, high-value transaction monitoring, and increased fraud monitoring during periods of higher fraud activity.

## Detailed Report

The complete **62-page EDA report** contains the detailed analysis, visualizations, statistical findings, insights, and recommendations.
