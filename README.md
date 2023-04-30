# CodeClause_Credit_Card_Fraud_Detection

This Python script uses machine learning models to detect fraudulent credit card transactions in a dataset. The dataset is loaded using the pandas library and preprocessed for machine learning by removing irrelevant features and rescaling the data.

## Dependencies
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn

## Usage
To use this script, ensure you have all the dependencies installed. Then, follow these steps:
Clone the repository to your local machine.
Open a terminal window and navigate to the directory where the script is saved.
Run the script by typing the following command: python credit_card_fraud_detection.py.
The script will load the dataset, preprocess the data, and apply two outlier detection models: Isolation Forest and Local Outlier Factor.
The script will print the number of errors for each model and display the classification report and accuracy score for each model.

## Dataset
The dataset used in this script is the Credit Card Fraud Detection dataset from Kaggle.
( Dataset Link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud )
The dataset contains credit card transactions made by European cardholders over a two-day period in September 2013. The dataset has 31 columns, with the Class column indicating whether the transaction was fraudulent (1) or valid (0).

## Example
Suppose you want to detect fraudulent credit card transactions in a dataset. You can use this script to preprocess the data and apply two outlier detection models to identify potential fraudulent transactions.
