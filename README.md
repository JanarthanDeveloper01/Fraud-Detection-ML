Fraud Detection Using Machine Learning
Project Overview

This project focuses on proactive fraud detection for financial transactions using machine learning techniques. The dataset contains over 6.3 million simulated transaction records.
The objective is to detect fraudulent transactions while minimizing false positives.

Dataset Description

The dataset includes:

Transaction type (CASH-IN, CASH-OUT, TRANSFER, DEBIT, PAYMENT)
Transaction amount
Account balances before and after transaction
Fraud label (isFraud)
Flagged fraud indicator (isFlaggedFraud)
Fraud cases represent approximately 0.13% of the dataset, making this a highly imbalanced classification problem.

Project Workflow

1️⃣ Data Cleaning

Checked for missing values

Outlier analysis using boxplots

Multicollinearity analysis using correlation matrix

2️⃣ Feature Engineering

Created balance difference features

Created error balance features

Extracted time-based features (hour, day)

3️⃣ Handling Class Imbalance

Applied SMOTE to balance training data

4️⃣ Model Development

Random Forest Classifier

5️⃣ Model Evaluation

Confusion Matrix

Precision, Recall, F1-score

ROC-AUC

Precision-Recall Curve

Feature Importance Analysis

Results

Strong fraud detection performance
High recall for fraud class
Excellent Precision-Recall curve performance
Key fraud indicators identified
Top Predictors:
  Balance inconsistencies
  Transaction amount
  Transfer and Cash-out transaction types

Business Recommendations

Real-time fraud detection system
Multi-factor authentication for high-risk transactions
Automated transaction monitoring
Continuous model retraining
Risk-based alert system

Technologies Used 

Python
Pandas
NumPy
Scikit-learn
Imbalanced-learn (SMOTE)
Matplotlib
Seaborn
