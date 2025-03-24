# Insurance Fraud Claims Dataset
# Dataset Description
- A synthetic dataset of 5,250 insurance claims for fraud analysis, with claimant details, claim amounts, dates, and fraud flags (~76.4% fraudulent).
- Originally 11 columns, reduced to 8, with 3 engineered features.

# Key Objectives
- Clean and preprocess data.
- Explore dataset structure and statistics.
- Test if fraudulent claims have larger amounts.
- Build a basic fraud prediction model.

# Visualization & Insights
- Histogram: Compared Claim_Amount for fraud (red) vs. non-fraud (blue); overlapping distributions with high variance.
- T-test: No significant difference in claim amounts (p > 0.05, example).
- Insight: Fraudulent claims dominate (76.4%), but amounts don’t clearly distinguish fraud.

# Expected Outcomes
- Cleaned dataset with features like State, Year, Month.
- Baseline Random Forest model (~70% accuracy).
- Further analysis needed for deeper fraud insights.
# Features
- Claimant_Name, Insurance_Type, Fraud_Category (1,237 missing), Claim_Amount ($280–$39,360), Claim_Date, Claim_Status, Fraud_Flag, State, Year, Month.
## Usage
- Clone repo, open insurance_fraud_analysis.ipynb, install pandas, numpy, seaborn, matplotlib, scikit-learn, scipy, and run.
