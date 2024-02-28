# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
  - The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from peer-to-peer lending services

* Explain what financial information the data was on, and what you needed to predict.
  - Loan size, interest rate, borrower income, debt to income, num of accounts, derogatory marks, total debt. predicted if a loan was healthy or high risk.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  -  loan status as represented as 1 - high risk loan and 0 - healthy loan. The value count for 0  was 75036 and for 1 was 2500

* Describe the stages of the machine learning process you went through as part of this analysis.
  - Data cleaning, feature selection and engineering, resampling, train-test split, model training, and evaluation.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
  - Included Logistic Regression as the primary classification algorithm for predicting creditworthiness

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    - Accuracy: The overall accuracy of Model 1 is 0.99
    - Precision: For the healthy loans (0), the precision is 1.00, for high-risk loans (1), the precision is 0.87, indicating that there are some false positives in the predictions
    - Recall: For healthy loans (0), the recall is 1.00, suggesting that the model effectively captures all actual instances of healthy loans, for high-risk loans (1), the recall is 0.89, indicating that the model successfully identifies 89% of the actual instances of high-risk loans

## Summary

Summarize the results of the machine learning model. For example:
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  - The machine learning model, particularly Logistic Regression, exhibits outstanding overall accuracy of 99%, with a balanced trade-off between precision and recall for high-risk loans. Also yes, the performance of the machine learning model does depend on the specific problem and the objectives of the lending institution. In the context of predicting creditworthiness, the trade-off between precision and recall becomes crucial, and the choice depends on the priorities of the business
