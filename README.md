# credit-risk-classification

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression model used to predict loan statuses. Specifically, I aim to determine the effectiveness of the model in classifying loans as either `0` (healthy loan) or `1` (high-risk loan). The dataset used for this analysis contains financial information about loans. This includes various features such as interest rate, borrower income, debt to income,	number of accounts,	derogatory marks,	total debt, and	I am trying to predict loan status.


## Results
The following is the results from the regression model:

Accuracy Score: 0.99
Precision Score for 0 (Healthy Loan): 1.00
Recall Score for 0 (Healthy Loan): 1.00
Precision Score for 1 (High-Risk Loan): 0.87
Recall Score for 1 (High-Risk Loan): 0.89

## Summary

The logistic regression model exhibits outstanding performance in predicting healthy loans (0), achieving perfect precision and recall. This indicates that the model is highly effective in identifying healthy loans without any false positives or false negatives. For high-risk loans (1), the model performs well, with precision and recall scores of 0.87 and 0.89. These metrics indicate that while the model is strong, there is room for improvement in identifying all high-risk loans accurately. Based on the results, I recommend using the logistic regression model for loan risk prediction. The model's exceptional performance in predicting healthy loans and strong performance in predicting high-risk loans make it a reliable tool for the company's loan approval process. The high overall accuracy of 99% further supports its effectiveness. 
