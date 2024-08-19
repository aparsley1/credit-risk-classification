# Module 12 Report

## Overview of the Analysis

- **Purpose of the Analysis:** The purpose was to develope a machine learning  model to predict credit risk associated with loans by identifying whether a loan is healthy or high-risk.
-**Financial Information:** This dataset included information such as loan size, interest rate, borrower income, dti ratio, number of accounts, derogatory marks, and total debt. The target variable was the loan status.
- **Machine Learning Process:**
  - **Data Preparation:** Data was split into training and testing sets.
  - **Modeling:** Logistic Regression was chosen as the algorithm.
  - **Evaluation:** Model performance was evaluated using accuracy, precision, recall, and a confusion matrix.

## Results

- **Logistic Regression Model:**
  - **Accuracy:** 99%
  - **Precision:**
    - Healthy Loans (0): 1.00
    - High-risk Loans (1): 0.84
  - **Recall:**
    - Healthy Loans (0): 0.99
    - High-risk Loans (1): 0.94
  - **F1-Score:**
    - Healthy Loans (0): 1.00
    - High-risk Loans (1): 0.89

## Summary

- **Best Performing Model:** The Logistic Regression model performed exceptionally well, particularly in predicting healthy loans with an F1-score of 1.00. The model is also strong in predicting high-risk loans with a recall of 0.94.
- **Model Recommendation:** Given the high accuracy and balanced performance across both classes, this Logistic Regression model is recommended. It effectively identifies high-risk loans, which is critical in minimizing financial risk. 

