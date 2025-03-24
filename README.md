# Insurance Fraud Claims Dataset
# Project Overview
- This repository contains a Python-based analysis of an insurance claims dataset to identify patterns of fraudulent behavior. 
- The project includes data preprocessing, exploratory data analysis (EDA), statistical testing, and a basic predictive model using a Random Forest Classifier.
- The dataset, Data Set.csv, consists of 5,250 insurance claims with details such as claim amount, insurance type, fraud category, and fraud flag.

# The goal is to:

- Investigate whether fraudulent claims differ significantly in amount from non-fraudulent claims.
- Build a simple predictive model to detect fraud.
- This project was developed using Python with libraries like Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, and Feature-engine.
# Key Preprocessing Steps
- Converted Claim_Date to datetime for temporal analysis.
- Dropped irrelevant columns: Claim_Description, Missing_Field, Claim_ID, Claimant_Address.
- Filled missing Fraud_Category values with "None".
- Extracted State, Year, and Month for additional analysis.
# Summary Statistics for Claim_Amount
- Count: 5,250
- Mean: $12,812.90
- Std Dev: $8,656.43
- Min: $280.94
- Max: $39,360.07
- 25th Percentile: $5,769.09
- 50th Percentile: $11,066.88
- 75th Percentile: $18,420.75

# Visualization & Insights
- Histogram: Compared Claim_Amount for fraud (red) vs. non-fraud (blue); overlapping distributions with high variance.
- T-test: No significant difference in claim amounts (p > 0.05, example).
- Insight: Fraudulent claims dominate (76.4%), but amounts don’t clearly distinguish fraud

# Expected Outcomes

- Cleaned dataset with features like State, Year, Month.
- Baseline Random Forest model (~70% accuracy).
- Further analysis needed for deeper fraud insights.

# Usage
Clone repo, open insurance_fraud_analysis.ipynb, install pandas, numpy, seaborn, matplotlib, scikit-learn, scipy, and run.
