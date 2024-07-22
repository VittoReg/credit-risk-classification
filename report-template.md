# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Purpose of the Analysis
- Test different machine learning model performance
- Find the most effective model for financial outcomes.

Financial information and prediction objectives
- Predictions on loan pay back
- Financial infomration in a wide range, such as loand, borrower details, payment status.

Variables to Predict
- Target variable, loan status: 0 (paid back in full) or 1 (defaulted) 

Machine Learning Process
1. Cleaning and preparing the data.
2. Choosing machine learning algorithms.
3. Training models on the data.
4. Evaluating performance by the use of accuracy, precision, and recall.
5. Testing and comparing models to identify the most suitable for the task.


Methods applied
- Logistic Regression
- Decision Trees
- Random Forest
- SVM
- Gradient Boost

Reuslts

Machine Learning Model 1: Logistic Regression
- Accuracy: 0.85
- Precision: 0.87
= Recall: 0.83

Machine Learning Model 2: Decision Tree
- Accuracy: 0.82
- Precision: 0.80
- Recall: 0.85

Machine Learning Model 3: Random Forest
- Accuracy: 0.88
- Precision: 0.90
- Recall: 0.86

Machine Learning Model 4: Support Vector Machine (SVM)
- Accuracy: 0.84
- Precision: 0.86
- Recall: 0.82

Machine Learning Model 5: Gradient Boosting
- Accuracy: 0.89
- Precision: 0.91
- Recall: 0.87

## Summary

Best Performing Model
- Gradient Boosting appears to haver highest accuracy (0.89), precision (0.91), and recall (0.87)

Performance dependence on problem
- Predicting defaults are optimal for reducing financial risks.

Recommendation
- Gradient Boosting proved to be superior.
- Great choice if you're aiming at minimizing defaults due to high recall score.
- Correctly predicting loans paid back in full.