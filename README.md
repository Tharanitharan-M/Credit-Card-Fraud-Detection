# Credit-Card-Fraud-Detection

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. This repo contains how we find different insights from the data and use ml algorithm to predict whether a transaction is fraud or not.

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Problem Statement

Link - [Credit Card Fraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Summary

- The **amount of all fraud transactions are below 2250** inorder to avoid suspicious.
- The fraud transactions are distributed throughout the time. So, there are **no solid relationships between the time and the fraud transactions**
- The dataset is **highly imbalanced**, there need to be a fair comparison to avoid overfitting in the model. Therefore, I took a sample 492 data from the legit transactions and used **Logistic Regression** ML algorithm to predict whether a transaction is legit or fraud.
- The Accuracy of this algorithm is **92.89%**
- We can increase the accuracy of the algorithm by using the Synthetic Minority Oversampling (SMOTE)
