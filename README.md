# Telco Customer Churn Prediction & Analysis

## Executive Summary
This project analyzes customer retention data from a telecommunications provider to identify key drivers of customer churn and build a predictive machine learning model. By uncovering patterns in tenure, contract types, and service charges, the goal is to provide actionable recommendations to reduce churn and improve overall customer lifetime value.

## Key Insights & Findings
* **Contract Type:** Customers on Month-to-Month contracts exhibit the highest churn rate compared to those on 1-Year or 2-Year plans.
* **Tenure:** New customers (0–12 months of tenure) are significantly more likely to cancel their subscriptions.
* **Pricing & Services:** Higher monthly charges, especially when coupled with fiber optic internet lacking technical support add-ons, correlate strongly with higher churn risk.

## Tech Stack
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest Classifier, Feature Scaling, Metrics)

## Repository Structure
```text
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   └── churn_analysis_eda_model.ipynb
├── reports/
│   └── Detailed_Project_Report.md
├── README.md
└── requirements.txt
