# Credit Card Fraud Detection and Analysis (with SQL + Tableau)

A comprehensive project analyzing a financial transaction dataset to uncover patterns in fraudulent activities using SQL (in Colab) for data processing and Tableau for visualization.

#  Dataset Overview
The dataset contains synthetic financial data including:

 Transactions: Date, amount, merchant info, location, and fraud labels

 User Info: Age, occupation, location (used for segmentation)

 Geographic & Temporal Details: State, city, transaction timestamp

 Target Variable: is_fraud (1 = fraud, 0 = legitimate)

 # Tools & Technologies
 Python (Pandas, PandasQL) – for SQL-like queries in Google Colab

SQL – used for slicing, aggregating, and binning data

Tableau – to visualize fraud patterns interactively

Jupyter / Colab – for SQL execution and preprocessing

| Theme                   | Finding                                                                                |
| ----------------------- | -------------------------------------------------------------------------------------- |
| **Overall Fraud Rate**  | \~12.75% of all transactions were fraudulent                                           |
| **High-Risk Time**      | Most frauds occur during **Late Night** (12–3AM) and **Night** (9PM–12AM)              |
| **Transaction Amount**  | Highest frauds between **\$201–\$2000**, especially \$501–\$1000                       |
| **Merchant Categories** | `shopping_net`, `grocery_pos`, and `misc_net` had fraud rates >25%                     |
| **State-wise Risk**     | Alaska, Nebraska, and Oregon top the fraud rate chart                                  |
| **Occupation Risk**     | Roles like `"Surveyor, minerals"` and `"System Analyst"` show higher fraud involvement |

# Tableau Dashboard Highlights
 Fraud vs Non-Fraud Summary (KPI Cards)

 Hourly Fraud Pattern (Time Bin)

 Monthly Fraud Trend

 State-wise Fraud Heatmap

 Fraud by Transaction Amount Bucket

 Merchant Category Fraud Rate

 Job vs Fraud Count

 # Project Goals
 Understand when, where, and how fraudulent transactions occur

Build SQL-based preprocessing pipeline

Deliver clear and interactive dashboards for fraud analysis

Support AI/ML model input generation with data insights

# Final Recommendations
Set amount-based fraud triggers for $201–$2000

Increase authentication for nighttime and online shopping

Factor location and job-based risk scoring in modeling

Use category segmentation as a fraud feature for ML models
