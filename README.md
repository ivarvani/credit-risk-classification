# credit-risk-classification

## Overview of the Analysis

# Credit Worthiness Model
* Purpose of the analysis was to build a model that can identify the creditworthiness of borrowers.
* The dataset was of historical lending activity from a peer-to-peer lending services company.
* The Data was based on the Borrowers_debt an borrowers_income and the interest rates,outstanding debt,etc 
* We were trying to predict if a loan was a high_risk loan or not
* Stages of the machine learning process used as part of this analysis:
1. Created the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
2. Split the data into training and testing datasets by using train_test_split.
3. LogisticRegression was used to create the model with the solver bieng the default "lbfgs"

## Results

describing the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  *  Model Accuracy: 0.99,
  *  Model Precision : 0.85
  *  Model Recall : 0.91



## Summary
* For high-risk loan Out of the predictions that the model predicts to be high risk loans only 85% of the predictions is correct thus the precision is 85%.(15% of times, where it predicted high risk loans the model predicted wrong) 
* In addition to that out of all the high risk loans that are present in the dataset,the model predicts 91% of them correctly.(recall is 91%). Which in real world is practical. 
Thus I would recommend the model.
