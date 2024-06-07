# Anomaly Detection: Identifying fraudulent bank credit card activity using Machine Learning

## Project Description

Detecting credit card fraud is a critical task in financial institutions. There is a variety of Machine Learning algorithms that financial analysts can use to detect when a transaction is fraudulent, in order to prevent substantial monetary losses and ensure the security of user data. This project aims to develop and evaluate different Machine Learning models that detect fraudulent credit card transactions effectively.

## Data

The original dataset can be found in the following link:
https://www.kaggle.com/datasets/christianpartal/credit-card-data

It contains data on real transactions made using credit cards in September 2013 by European cardholders.

Features include “Time”, “Amount” (monetary amount of the transaction, in €), and “Class” (which indicates if the transactions are fraudulent or not). Normal, valid transactions will have a value of 0, fraudulent transactions a value of 1.
There are additional 28 variables related to the user’s bank account, financial behaviour and additional transaction details, which for data privacy have been renamed and anonymized through a Principal Component Analysis (PCA) technique, which transforms the original features into a set of new, anonymous features while still preserving the essential patterns and structures. Therefore these features will just appear as V1, V2,…, V28 in the analysis.

## Machine Learning Models

A variety of Jupyer Nothebooks are provided, first doing some Exploratory Data Analysis on the data we have, and then testing both Supervised and Unsupervised Machine Learning models which we train to identify fraud.
We adjust the models to the specific needs of the analysis and compare the results of each to decide which is the most appropriate.
Once trained, the models can be used to predict if future transactions should be considered fraudulent or not. Depending on the institutions' particular needs and preferences between precision and recall, some model variations will be more suited than others.
Some institutions may prefer to detect fraud at any cost, but thist comes at a greater risk of false positives.
