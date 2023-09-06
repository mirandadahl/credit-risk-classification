# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to determine the significance of using various techniques to train and evaluate a model based on loan risk. The financial information that this data was collected from a peer-to-peer lending services company collected from a historical lending activity. Looking at this the goal was to predict 'loan_status,' which represents whether a loan is in good standing (0) or has defaulted (1). Variables include 'loan_size,' 'interest_rate,' 'borrower_income,' 'debt_to_income,' 'num_of_accounts,' 'derogatory_marks,' 'total_debt,' and 'loan_status.'A model used included Logistic Regression model.

## Results

* Machine Learning Model 1 (Logistic Regression Model with the Original Data):
Class 0: 1.00
Class 1: 0.86
Recall:
Class 0: 1.00
Class 1: 0.99

* Machine Learning Model 2 (Logistic Regression Model with Resampled Training Data):
Precision:
Class 0: 1.00
Class 1: 0.85
Recall:
Class 0: 0.99
Class 1: 0.99

## Summary

In summary, I initially built a logistic regression model to predict loan status and assessed its performance. Due to class imbalance in the target variable, I applied random oversampling to balance the classes and built a resampled logistic regression model. Finally, I evaluated the resampled model using various metrics to assess its performance.

The results here were nearly the same with both methods used. The healthy loans are correctly predicted at 100% and the high-risk loans are correctly predicted at 85-86%.

For both classes 0 and 1, the recall is high (0.99), suggesting that the model correctly identifies the majority of instances of both classes. Meaning the model rarely misses instances of either class.

