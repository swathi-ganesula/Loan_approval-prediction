Loan Approval Prediction Project

This project focuses on predicting whether a loan application will be approved
based on applicant and loan-related information using machine learning.

Problem Statement
The objective is to build a classification model that predicts loan approval
status based on demographic and financial features of applicants.

Dataset
The project uses training and testing CSV datasets that contain applicant
details such as income, education, loan amount, credit history, and loan status.

Approach
The dataset was loaded and cleaned to handle missing values.
Categorical features were encoded into numerical form.
The data was split into training and testing sets.
A Decision Tree classifier was trained on the training data.
Model performance was evaluated using accuracy on test data.

Model Used
Decision Tree Classifier

Result
The model was able to learn patterns from the data and predict loan approval
status with good accuracy on unseen test data.

Files Included
loan_approval_prediction.ipynb – Main notebook
train_dataset.csv – Training dataset
test_dataset.csv – Testing dataset
requirements.txt – Required libraries
