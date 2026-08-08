# Credit Card Transaction Analysis – EDA

Exploratory Data Analysis of credit card transaction data to understand customer demographics, card characteristics, merchant patterns, transaction behaviour, and fraud-related patterns.

## Dataset

The analysis uses four datasets:

* **Customer:** 25,000 records, 12 columns
* **Cards:** 32,457 records, 10 columns
* **Transaction:** 250,000 records, 20 columns
* **Merchant:** 500 records, 9 columns

## EDA Process

### 1. Data Quality Assessment

* Dataset structure and dimensions
* Data types
* Missing values
* Duplicate records
* Outlier investigation
* Date conversion

### 2. Univariate Analysis

Analysis of individual variables using:

* Histograms
* Count plots
* Distribution plots

Variables analyzed include age, annual income, credit limit, transaction amount, payment method, fraud flag, card type, card network, merchant category, and merchant risk level.

### 3. Bivariate Analysis

Relationships between two variables using:

* Scatter plots
* Box plots

Examples:

* Age vs Annual Income
* Credit Limit vs Transaction Amount
* Card Type vs Credit Limit
* Payment Method vs Transaction Amount
* Merchant Category vs Transaction Amount
* Fraud Flag vs Transaction Amount

### 4. Categorical vs Categorical Analysis

Used cross-tabulation and heatmaps to analyze relationships such as:

* Card Type vs Payment Method
* Customer Segment vs Fraud Flag
* Merchant Category vs Fraud Flag

### 5. Multivariate Analysis

Analyzed multiple variables simultaneously using visualizations such as:

* Age vs Transaction Amount by Fraud Flag
* Annual Income vs Transaction Amount by Customer Segment
* Credit Limit vs Transaction Amount by Card Type
* Merchant Category vs Transaction Amount by Fraud Flag

### 6. Correlation Analysis

The correlation matrix includes:

* Age
* Annual Income
* Credit Limit
* Transaction Amount
* Merchant Rating
* Fraud Flag
* Is International

The strongest observed relationships include:

* Annual Income & Credit Limit: **0.43**
* Transaction Amount & Fraud Flag: **0.27**
* Age & Annual Income: **0.23**

## Data Integration

The four datasets were merged using common identifiers to create a final analytical dataset containing **250,000 rows and 47 columns**. Duplicate columns created during merging were reviewed and unnecessary columns were removed.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Structure

```text
Credit-Card-Transaction-Analysis/
│
├── README.md
├── EDA/
│   └── Credit_card_transaction_analysis.pdf
│
├── Notebook/
│   └── Credit_card_transaction_analysis.ipynb
│
└── Dataset/
    └── README.md
```

## Report

The complete **62-page EDA report** contains the Python code, data quality checks, statistical analysis, visualizations, relationship analysis, and correlation analysis.

