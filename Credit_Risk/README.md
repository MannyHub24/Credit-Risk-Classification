
# Module 20 Challenge: Credit Risk Classification - Logistic Regression Model

Overview of the Analysis

In this analysis, a logistic regression machine learning model was trained to predict credit risk using historical loan data. The goal of this analysis was to determine whether loans are healthy (0) or high risk (1) based on various borrower financial attributes such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

The dataset was split into features (X) and labels (y), where the loan_status column served as the label. The data was then divided into training and testing sets using a random state of 1 to ensure reproducibility. A logistic regression model was trained on the training data and evaluated using the testing data.

The logistic regression model was chosen because it is well-suited for binary classification problems like predicting credit risk.


Results

Machine Learning Model: Logistic Regression


- Precision:

Class 0 (Healthy Loans): 1.00

Class 1 (High-Risk Loans): 0.84


- Recall:

Class 0 (Healthy Loans): 0.99

Class 1 (High-Risk Loans): 0.94


- F1-Score:

Class 0 (Healthy Loans): 1.00

Class 1 (High-Risk Loans): 0.89


- Accuracy: 0.99

Summary

The logistic regression model performed extremely well, achieving an overall accuracy of 99%. It predicted healthy loans (0) almost perfectly, with precision and recall near 1.00. For high-risk loans (1), it achieved a strong recall of 0.94 and a precision of 0.84, meaning it correctly identified most of the high-risk loans while keeping false positives relatively low.

Since predicting high-risk loans correctly is critical to minimizing potential financial losses, the model’s high recall for the high-risk class is particularly important. Therefore, I recommend using this logistic regression model for credit risk classification, as it is both accurate and reliable in predicting loan health status.

