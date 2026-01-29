Credit Card Fraud Detection
Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
The dataset is highly imbalanced, with fraud cases representing a very small percentage of total transactions. The goal is to build a model that accurately identifies fraudulent transactions while minimizing false positives.

Dataset Description

Dataset Name: Credit Card Fraud Detection

Source: Kaggle

Total Transactions: 284,807

Fraudulent Transactions: 492

Non-Fraudulent Transactions: 284,315
 Features
Feature	Description
V1 – V28	Principal Component Analysis (PCA) transformed features
Time	Time elapsed between the transaction and the first transaction
Amount	Transaction amount
Class	Target variable (0 = Legitimate, 1 = Fraud)

Note: Due to confidentiality reasons, original feature names are not available.

Technologies Used

Python

Google Colab / Jupyter Notebook

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

 Project Workflow

Data Loading

Load the CSV dataset

Verify dataset integrity

Exploratory Data Analysis (EDA)

Check class imbalance

Visualize transaction amounts

Analyze fraud vs non-fraud patterns

Data Preprocessing

Feature scaling (StandardScaler)

Train-test split

Handling class imbalance (if applied)

Model Training

Logistic Regression / Decision Tree / Random Forest (or any chosen model)

Fit model on training data