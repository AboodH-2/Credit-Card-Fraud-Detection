
# Credit Card Fraud Detection Using Logistic Regression

## Overview

This project is a **Credit Card Fraud Detection** system developed using **Logistic Regression**. The goal of this project is to detect fraudulent credit card transactions by classifying them as either "fraudulent" or "non-fraudulent" based on historical transaction data. The model is trained using a dataset that contains various transaction details such as transaction amount, card type, time of transaction, etc.

## Dataset

This project uses the **Credit Card Fraud Detection** dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). The dataset consists of transactions made by credit cards in September 2013 by European cardholders. It contains **284,807 transactions**, out of which **492 are fraudulent**.

### Features:

- **Time**: The number of seconds elapsed between this transaction and the first transaction in the dataset.
- **V1, V2, ..., V28**: These are anonymized features (engineered through PCA).
- **Amount**: The transaction amount for the current transaction.
- **Class**: 1 indicates a fraudulent transaction, 0 indicates a non-fraudulent transaction.

## Technologies Used

- **Python**: Programming language used for the development.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing the Logistic Regression model and other machine learning utilities.
- **Jupyter Notebook**: Used for running and documenting the analysis.


1. Clone the repository:
   ```bash
   git clone https://github.com/AboodH-2/credit-card-fraud-detection.git
