# Module 12 Report Template

## Overview of the Analysis

The analysis aimed to develop a machine learning model to classify loans as "healthy" (class 0) or "high-risk" (class 1) based on financial data, helping institutions make informed choices on loan approval. The dataset includes loan outcomes as the target variable and features representing loan characteristics.

This prediction model used logistic regression to classify loans as "healthy" and "high risk". This model did achieve 99% accuracy, but there is still much information to consider with this model.


## Results
•	Accuracy: Reflects the overall correctness of predictions across all classes. This model shows a high level of accuracy of 99% for healthy loans.

•	Precision
o	Class 0 (Healthy Loans): High precision means that most loans predicted as healthy were indeed healthy. This model showed that healthy loan identification precision was 1.00, which is very good. 
o	Class 1 (High-Risk Loans): Indicates the proportion of loans predicted as high-risk that were truly high-risk. This model shows the precision for these loans was 0.86.

•	Recall
o	Class 0: Represents the percentage of actual healthy loans correctly identified as healthy. The recall for these loans were shown to be 1.0, which is very good.
o	Class 1: Represents the percentage of actual high-risk loans correctly identified as high-risk. The recall on these loans was 0.94.

•	F1-Score: Provides a harmonic mean of precision and recall, offering a balanced measure of the two.
•	This model was shown to be highly reliable with only 108 misclassifications of loans. This was out of the 15,508 loans. 


## Summary

The logistic regression model is suitable if the goal is balanced performance between predicting healthy and high-risk loans.

If High-Risk Loan FN Is Critical:

Recall for class 1 (86%) should improve via dataset rebalancing or hyperparameter tuning.
If Healthy Loan FP Is a Concern:

Class 1 precision (90%) is acceptable for minimizing false alarms.
Performance Assessment
Performs better for healthy loans (class 0) with recall at 99% and F1-score at 100%.
Class 1 (high-risk loans) precision is 86% suggests room for improvement, but recall (94%) is a promising number.
Recommendation
Deploy if the current balance meets business needs. For better class 1 identification, explore threshold adjustments or advanced models (e.g., Random Forest, Gradient model, boosting).
