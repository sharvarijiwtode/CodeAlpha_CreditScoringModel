CreditScoringModel

## Project: Credit Scoring Prediction

This project is submitted as part of the **Machine Learning Internship at CodeAlpha**. The goal is to build a classification model that can predict whether a customer is a good or bad credit risk based on their financial and personal attributes.

## Dataset:

- Name: German Credit Data
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)
- Rows: 1000
- Features: 20 (Categorical and Numerical)
- Target Column: `Credit_risk`  
  - `0`: Good Credit  
  - `1`: Bad Credit

## Model Used:

- Algorithm: Random Forest Classifier
- Preprocessing:
  - Label Encoding of categorical features
  - Feature Scaling using StandardScaler
- Train-Test Split: 80% Train / 20% Test

## Performance Metrics:

Accuracy ~76–79%
Precision: 0.79
Recall: 0.82
F1 Score: 0.80
ROC AUC Score ~0.85

## Requirements:

Install the required libraries:

bash
!pip install pandas scikit-learn matplotlib seaborn

## Run the code

python credit_scoring_model.py
