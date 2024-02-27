# Credit-Risk-Classification
## Credit Risk Analysis

### Overview

This project involves a credit risk analysis using logistic regression. The process includes splitting the data into training and testing sets, creating a logistic regression model with the original data, and generating a credit risk analysis report.

#### Split the Data into Training and Testing Sets

- **Read Data:**
   - Read "lending_data.csv" from the Resources folder into a Pandas DataFrame.
   - Create labels set (y) from "loan_status" column.
   - Create features set (X) from remaining columns.

- **Data Split:**
   - Use train_test_split to split data into training and testing datasets.

#### Create a Logistic Regression Model with the Original Data

- **Model Fit:**
   - Fit a logistic regression model using training data (X_train and y_train).

- **Predict and Evaluate:**
   - Save predictions for testing data labels (X_test).
   - Evaluate model performance:
      - Generate a confusion matrix.
      - Print the classification report.
      - Answer a question regarding model predictions.

#### Write a Credit Risk Analysis Report

- **Results:**
  - Accuracy score, precision score, and recall score listed in a bulleted list.

- **Summary:**
  - Summarize machine learning model results.
  - Provide justification for recommending or not recommending the model for company use.

---

## Summary

1. **Data Split:**
   - Read data and split into training and testing sets.

2. **Logistic Regression Model:**
   - Fit model, predict, and evaluate performance.

3. **Analysis Report:**
   - Overview, results, and summary with justification for model recommendation.
