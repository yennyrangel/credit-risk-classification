# Modulo 20: Credit Risk Analysis Report

## Overview of the Analysis

### Purpose of the Analysis:
The purpose of this credit risk analysis is to develop machine learning models that can predict whether a loan is high-risk (1) or healthy (0) based on various financial features. The goal is to assist in evaluating credit risk and making informed lending decisions.

### Financial Information and Prediction Target:
The dataset contains information on loans, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The target variable is "loan_status," where 0 represents a healthy loan and 1 represents a high-risk loan.

### Stages of the Machine Learning Process:
1) Data Loading and Preprocessing: Loaded the dataset, separated features and labels, and split the data into training and testing sets.
2) Model Training: Created a Logistic Regression model and trained it on the original training data.
3) Model Evaluation: Evaluated the model's performance using metrics such as balanced accuracy, precision, recall, and the classification report.
4) Resampling: Addressed class imbalance by using the RandomOverSampler to resample the training data.
5) Retrained and Re-evaluated Model: Trained the Logistic Regression model on the resampled data and re-evaluated its performance.

## Results

### Logistic Regression Model Performance:

* Model Accuracy Score: 99%
* Healthy Loan Predictions
  Precision: 100%
  Recall: 100%
* High-Rish Loan Predictions
  Precision: 86%
  Recall: 91%

## Summary

1) Overall Model Performance:
   The logistic regression model trained on the original data demonstrates excellent performance with a high accuracy score of 99%.
2) Performance on Healthy Loans (0):
   Perfect precision and recall (100%) indicate that the model accurately identifies healthy loans.
3) Performance on High-Risk Loans (1):
   The model shows strong performance with a precision of 86% and recall of 91% for high-risk loans.

### Recommendation:

The logistic regression model trained on the original data appears to perform exceptionally well for both healthy and high-risk loans. The high precision and recall for both classes suggest a balanced predictive ability. However, the decision to use this model depends on the specific goals and priorities of the lending institution.

### Conclusion:
Given the overall high performance of the logistic regression model and its balanced predictions for both healthy and high-risk loans, it is recommended for practical use in credit risk assessment. However, continuous monitoring, validation, and possibly incorporating additional features or models could further enhance the robustness and accuracy of the credit risk prediction system.