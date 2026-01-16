# credit-card-fraud-detection
# Credit Card Fraud Detection using Machine Learning

## Overview
Credit card fraud detection is a critical real-world machine learning problem due to highly imbalanced data and the high cost of misclassification.  
This project builds a binary classification model to identify fraudulent transactions using supervised machine learning techniques.

## Problem Statement
To classify a credit card transaction as:
- Fraudulent (1)
- Legitimate (0)

based on transaction features.

## Approach
- Performed data understanding and statistical analysis
- Analyzed class imbalance in the dataset
- Used undersampling to balance fraud and legitimate transactions
- Trained a Logistic Regression model as a strong baseline
- Evaluated model performance on unseen test data

## Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn

## Dataset
- Credit Card Transactions Dataset
- Highly imbalanced real-world dataset

## Model Evaluation
- Accuracy on training and test data
- Emphasis on understanding false positives vs false negatives

## Key Learnings
- Handling imbalanced datasets
- Importance of correct metric selection
- End-to-end ML workflow from data loading to evaluation

## Future Scope
- Use ensemble models such as Random Forest and XGBoost
- Apply advanced sampling techniques like SMOTE
- Deploy as a real-time fraud detection API
