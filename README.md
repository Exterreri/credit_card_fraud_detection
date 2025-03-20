# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is the **Credit Card Fraud Detection** dataset from Kaggle, which contains transactions made by European cardholders in September 2013.

## Project Overview

- **Dataset:** Credit card transactions with features extracted using PCA.
- **Goal:** Develop a model to accurately classify fraudulent transactions.
- **Challenges:** Highly imbalanced dataset (fraud cases are only ~0.17% of total transactions).

## Models Used

1. **Random Forest**
2. **SMOTE + Random Forest**
3. **XGBoost**
4. **Isolation Forest (Anomaly Detection)**

## Exploratory Data Analysis (EDA)

- **Distribution of Transaction Amounts**
- **Imbalance Analysis**
- **Feature Correlations (Heatmap)**
- **Boxplots of Key Features**
- **Time-based Analysis of Transactions**

## Evaluation Metrics

To handle class imbalance, the models are evaluated using:

- **Precision-Recall Curve & AUC (PR AUC)**
- **F1-score**
- **Recall (Sensitivity)**
- **Confusion Matrix**
