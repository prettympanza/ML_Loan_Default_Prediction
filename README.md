Loan Default Prediction

Project Overview:

This project predicts whether loan applicants will default using their personal, financial, and credit history information. It helps lenders identify high-risk borrowers and make informed decisions.

Objectives:

•	Detect high-risk loan applicants before approval.

•	Understand key factors contributing to loan defaults.

•	Provide actionable business insights for risk management.

•	Establish a baseline predictive model and evaluate performance.

Dataset:

•	Numerical Features: person_age, person_income, person_emp_length, loan_amnt, loan_int_rate, loan_percent_income, cb_person_cred_hist_length

•	Categorical Features: person_home_ownership, loan_intent, loan_grade, cb_person_default_on_file

•	Target Variable: loan_status (0 = Non-default, 1 = Default)

Methodology:

1.	Data Cleaning & Preprocessing:
   
    o	Fill missing values and remove duplicates.

    o	Encode categorical variables and scale numerical features.

2.	Exploratory Data Analysis (EDA):
   
    o	Visualize distributions of numerical and categorical features.

    o	Examine correlations, outliers, and multicollinearity (VIF analysis).

    o	Identify key drivers of loan default.

3.	Modeling:
   
    o	Train baseline Logistic Regression model.

    o	Address class imbalance using class weighting.

    o	Adjust decision threshold to improve default detection.

4.	Evaluation:
   
    o	Metrics: Accuracy, Precision, Recall, F1-score.

    o	Confusion matrix visualization.

    o	Threshold tuning improved recall for defaulters from 0.57 → 0.72.

Key Insights:

o	Lower income and higher loan-to-income ratio increase default risk.

o	Renters and certain loan intents (medical, debt consolidation) are more likely to default.

o	Larger loan amounts are correlated with higher default probability.

o	Threshold adjustment improves detection of high-risk borrowers.


