# Module 12 Report Template

## Overview of the Analysis:
The purpose of this analysis was to build machine learning models to predict whether a loan from a peer-to-peer lending services company is likely to be paid or not. The financial information the data was based on includes various features such as loan amount, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt, and the target variable to predict was the loan status (either fully paid or charged off). The data was highly imbalanced, with only a small percentage of loans being charged off.

The stages of the machine learning process for this analysis included data preprocessing, splitting the data into training and testing datasets, training and testing machine learning models, and evaluating the performance of the models using various metrics.

Two machine learning models were built and tested, including:

Machine Learning Model 1: Logistic Regression Model with Original Data

Balanced Accuracy: 0.994
Precision for Minority Class: 0.85
Recall for Minority Class: 0.91

Machine Learning Model 2: Logistic Regression Model with Resampled Data

Balanced Accuracy: 0.993
Precision for Minority Class: 0.99
Recall for Minority Class: 0.99

## Summary:
Both machine learning models achieved high balanced accuracy scores, with the model trained on resampled data achieving a slightly lower score than the model trained on original data. However, the model trained on resampled data had much higher precision and recall scores for the minority class than the model trained on original data.

Since the purpose of the analysis is to predict which loans are likely to be charged off, it is more important to correctly identify the minority class (charged off loans) than the majority class (fully paid loans). Therefore, the model trained on resampled data is recommended as it achieved higher precision and recall scores for the minority class. However, further analysis and feature engineering may be necessary to improve the model's performance even further.
