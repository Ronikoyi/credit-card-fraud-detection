# Credit Card Fraud Detection System

## Project Overview
A machine learning solution for credit card fraud detection, using a dataset of European credit card transactions. The project demonstrates the development of a model that achieves 82.65% fraud detection while maintaining a low 0.02% false alert rate.

## Dataset
- 284,807 credit card transactions
- 492 fraudulent cases (0.172% of total)
- 28 PCA-transformed features + Time and Amount
- Data anonymized for confidentiality
- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)

## Key Features
- Comprehensive EDA with visualization of class imbalance and feature distributions
- Temporal analysis of fraud patterns
- Feature importance analysis identifying key fraud indicators
- Model comparison (Logistic Regression, Random Forest, XGBoost)
- Business-focused evaluation metrics

## Results
The final XGBoost model achieved:
- 82.65% fraud detection rate
- 0.02% false alert rate
- F1 Score: 0.848
- AUPRC: 0.873
- ROC-AUC: 0.978

## Technical Implementation
- Python 3.x
- Key Libraries:
  - scikit-learn
  - XGBoost
  - pandas
  - numpy
  - matplotlib
  - seaborn

## View the Notebook
- [View on GitHub](https://github.com/Ronikoyi/credit-card-fraud-detection/blob/main/Credit%20Card%20Fraud%20Detection.ipynb)
