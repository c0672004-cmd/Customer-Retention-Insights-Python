# Telecom Customer Portfolio Retention & Revenue Risk Analysis

## Project Overview
This project addresses a critical corporate finance challenge: mitigating revenue loss caused by contract-stage customer churn. In telecom and subscription business models, customer attrition directly decays Monthly Recurring Revenue (MRR) and reduces the return on Customer Acquisition Cost (CAC). 

By executing an Exploratory Data Analysis (EDA) pipeline in Python, this project identifies key churn drivers across contract structures, payment friction, and demographic risk profiles to optimize customer lifetime value (LTV).

## Financial & Business Implications
* **Revenue Protection**: Moving customers away from high-churn contract structures helps lock in predictable recurring cash flows.
* **Transaction Friction Mitigation**: Quantifying the financial risk of manual transaction streams (Electronic Checks) vs. frictionless automated billing.
* **Portfolio Optimization**: Pinpointing high-risk demographic cohorts to deploy targeted, cost-effective retention budgets.

## Data Pipeline & Integrity Framework
To ensure accurate statistical reporting, a robust pre-processing pipeline was constructed:
* **String Normalization**: Applied lambda functions utilizing text-stripping (`.strip()`) and casing transformation (`.lower()`) to erase human data-entry anomalies.
* **Financial Data Reconstruction**: Converted hidden string fields in billing columns into numeric types, safely imputing blank spaces using the data's **median** to protect averages from outlier skews.

## Executive Insights & Recommendations (As per Project Guidelines)
1. **Contract Structure Vulnerability**: Month-to-month contracts experience significantly higher churn velocity than long-term alternatives. Implementing incentives to secure structured commitments is critical to protecting contract recurring cash flows.
2. **Payment Channel Friction**: Manual payment methods—specifically Electronic Checks—exhibit massive attrition rates. Transitioning these clients to automated clearing house (ACH) paperless billing or automatic credit card pipelines will systematically reduce billing failures.
3. **Cohort Concentration Risk**: Unmarried profiles and accounts without dependents present elevated operational risk. Corporate acquisition spend should prioritize sticky, high-LTV family units while applying protective retention budgets to high-risk segments.

## Youtube Video
[See the Youtube Video Here](https://youtu.be/He__uQ4RYg4)
