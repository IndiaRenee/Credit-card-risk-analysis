# Credit-card-risk-analysis
Credit card transaction risk analysis using Tableau to identify abnormal spending behavior and potential fraud patterns across 550K+ transactions.
# Credit Card Transaction Risk Analysis

![Dashboard Preview](images/dashboard-preview.png)

## Project Overview
This project analyzes credit card transaction activity to identify unusual spending behavior and potential fraud indicators. Using a dataset of over **550,000 transactions**, the analysis explores transaction patterns, spending behavior, and deviations from typical customer activity.

The goal of this project is to simulate how financial institutions monitor transaction data to detect suspicious activity and high-risk accounts.

## Dashboard
View the interactive Tableau dashboard here:

[https://public.tableau.com/views/Credit_card_risk_dashboard/CreditCardTransactionRiskAnalysisDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]

The dashboard highlights:
- total transaction volume
- average transaction value
- daily transaction activity trends
- spending by merchant category
- accounts with unusually high-value transactions

## Dataset
The dataset contains simulated credit card transactions including:

- transaction date and time
- credit card number
- merchant
- merchant category
- transaction amount
- customer demographic information
- transaction location data

The dataset includes **555,719 transactions** used to explore spending patterns and potential risk indicators.

## Tools Used
- **Tableau Public** – dashboard development and visualization
- **CSV dataset** – transaction data
- **GitHub** – project documentation and portfolio hosting

## Analysis Approach

### 1. Data Cleaning
The dataset was cleaned to ensure proper formatting and consistency:
- removed unnecessary fields (e.g., date of birth)
- corrected data types for transaction identifiers
- ensured transaction records were unique

### 2. Baseline Customer Behavior
Baseline metrics were established to understand normal transaction patterns:

- total transaction count
- average transaction value
- daily transaction activity

These baselines help analysts identify deviations that may indicate risk.

### 3. Spending Pattern Analysis
Transaction data was analyzed by merchant category to understand how spending varies across categories such as:

- groceries
- shopping
- gas
- entertainment
- travel

This helps identify unusual spending behavior within specific categories.

### 4. High-Value Transaction Monitoring
Transactions over **$500** were analyzed to identify accounts with repeated high-value purchases.

This step simulates how financial institutions flag accounts that may require further review.

### 5. Transaction Trend Monitoring
Daily transaction volume was analyzed to observe spikes in activity that could indicate unusual spending patterns or seasonal behavior.

## Key Insights

- The dataset contains **555,719 transactions** totaling over **$38 million in spending**.
- The average transaction value is approximately **$69.39**.
- Grocery and shopping categories represent the largest share of total spending.
- Certain accounts exhibit significantly higher transaction values and frequency compared to typical users.
- Periods with spikes in transaction activity may indicate seasonal spending behavior or potential anomalies.

## Project Purpose
This project demonstrates how transaction data can be used to:

- establish baseline customer behavior
- detect deviations from normal spending patterns
- identify potential high-risk accounts
- build monitoring dashboards used in financial risk analysis.

## Future Improvements
Potential extensions of this project include:

- implementing statistical anomaly detection
- building customer risk scoring models
- incorporating geographic transaction analysis
- using Python or SQL for deeper fraud pattern detection

## Author
India Moore
