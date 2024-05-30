# Anomaly Detection: Identifying fraudulent bank credit card activity using Machine Learning

## Project Description
Detecting credit card fraud is a critical task in financial institutions. There is a variety of Machine Learning algorithms that financial analysts can use to detect when a transaction is fraudulent, in order to prevent substantial monetary losses and ensure the security of user data. This project aims to develop and evaluate several Machine Learning models that detect fraudulent credit card transactions effectively. The dataset used in this project is real and consists of anonymized credit card transactions. This project is an example of Supervised Learning, as transaction observations are labelled as either normal or fraudulent.

## Data

The original dataset can be found in the following link:
https://www.kaggle.com/datasets/christianpartal/credit-card-data

Features include “Time”, “Amount” (monetary amount of the transaction, in €), and “Class” (which indicates if the transactions are fraudulent or not). Normal, valid transactions will have a value of 0, fraudulent transactions a value of 1.
There are additional 28 variables related to the user’s bank account, financial behaviour and additional transaction details, which for data privacy have been renamed and anonymized through a Principal Component Analysis (PCA) technique, which transforms the original features into a set of new, anonymous features while still preserving the essential patterns and structures. Therefore these features will just appear as V1, V2,…, V28 in our analysis.
