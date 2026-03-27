# Credit Card Fraud Detection

## Overview
This project implements a **machine learning** for detecting fraudulent credit card transactions. It focuses on **data preprocessing, feature engineering, model training, evaluation, and prediction**. The project is fully backend-oriented and **does not include a user interface (UI)**.

---

## Features
- Data preprocessing and scaling
- Handling class imbalance
- Multiple classification models:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Predictive pipeline for new transactions
- Easy integration for API-based systems

---

## Dataset
- Uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.
- Features:
  - Numerical: `V1`–`V28`
  - `Time`, `Amount`
  - Target: `Class` (0 = legitimate, 1 = fraud)
- Highly imbalanced dataset; fraudulent transactions are rare.

---

## Models used
- XGBoost : high-performance
- SMOTE : class balancing


## Evaluation Metrics
- Accuracy : 99%
- Precision : 96%
- Recall : 77%
- ROC-AUC : 88%
- F1-Score : 0.86%


