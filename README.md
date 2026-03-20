Loan Default Prediction (Machine Learning Project)

Project Overview:

This project develops a machine learning model to predict whether loan applicants will default using personal, financial, and credit history data. The goal is to help lenders identify high-risk borrowers and make informed, data-driven decisions.

Objectives:

Detect high-risk loan applicants before approval

Understand key factors contributing to loan default

Provide actionable insights for risk management

Build and evaluate a predictive model

Dataset:

Dataset size: 32,581 observations

Numerical Features: person_age, person_income, person_emp_length, loan_amnt, loan_int_rate, loan_percent_income, cb_person_cred_hist_length

Categorical Features: person_home_ownership, loan_intent, loan_grade, cb_person_default_on_file

Target Variable: loan_status (0 = Non-default, 1 = Default)

Methodology:

Data Cleaning & Preprocessing:

Fill missing values and remove duplicates

Encode categorical variables and scale numerical features

Exploratory Data Analysis (EDA):

Visualise distributions of numerical and categorical features

Examine correlations, outliers, and multicollinearity (VIF analysis)

Identify key drivers of loan default

Modeling:

Train baseline Logistic Regression model

Address class imbalance using class weighting

Apply threshold tuning (0.50 → 0.30) to improve detection of defaulters

Evaluation:

Metrics: Accuracy, Precision, Recall, F1-score

Achieved ~87% accuracy on test data

Confusion matrix visualisation

Threshold tuning improved recall for defaulters from 0.57 → 0.72

Key Insights:

Lower income and higher loan-to-income ratio increase default risk

Renters and certain loan intents (medical, debt consolidation) are more likely to default

Larger loan amounts are correlated with higher default probability

Threshold adjustment improves detection of high-risk borrowers, with a trade-off in precision and overall accuracy

Business Impact:

Enables proactive identification of high-risk borrowers

Supports data-driven credit approval decisions

Helps reduce financial losses from loan defaults
