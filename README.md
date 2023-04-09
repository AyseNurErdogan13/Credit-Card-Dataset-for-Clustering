# Credit-Card-Dataset-for-Clustering
 Customers segmentation based on their credit card usage behavior. We will begin with some initial concepts, going to dataset exploratory analysis, passing through data preprocessing, grouping customers into clusters, and at the end, we will perform an analysis of the clusters, plus marketing suggestions.
## Dataset

The Credit Card Dataset consists of 8950 rows and 18 columns, containing credit card usage behavior data for credit card holders. The dataset includes features such as credit limit, gender, marital status, education, age, payment history, and amount of bill statement.
The link to the dataset is available on Kaggle. 
[Credit Card Dataset](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata/code)
## Dataset Dictionary

Credit Card Dataset for Clustering

- CUST_ID: Identification of Credit Card holder (Categorical)
- BALANCE: Balance amount left in their account to make purchases
- BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- PURCHASES: Amount of purchases made from account
- ONEOFF_PURCHASES: Maximum purchase amount done in one-go
- INSTALLMENTS_PURCHASES: Amount of purchase done in installment
- CASH_ADVANCE: Cash in advance given by the user
- PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- PURCHASESINSTALLMENTSFREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- CASHADVANCEFREQUENCY: How frequently the cash in advance being paid
- CASHADVANCETRX: Number of Transactions made with "Cash in Advanced"
- PURCHASES_TRX: Number of purchase transactions made
- CREDIT_LIMIT: Limit of Credit Card for user
- PAYMENTS: Amount of Payment done by user
- MINIMUM_PAYMENTS: Minimum amount of payments made by user
- PRCFULLPAYMENT: Percent of full payment paid by user
- TENURE: Tenure of credit card service for user

## Project Goal

The goal of this project is to use unsupervised learning techniques to cluster customers based on their credit card usage behavior. The clustering will be based on the following features:

## Credit Limit
- Age
- Education
- Marital Status
- Gender
- Payment History
- Amount of Bill Statement
The project will explore different clustering algorithms and compare their performance in terms of cluster quality and interpretability.

## Project Aim
Initially, our focus will be to segment customers according to their similarities. After that, we will analyze this segmentation and define an effective credit card marketing strategy.
## Files

The repository contains the following files:

Dataset.csv: The Credit Card Dataset
Credit Card Dataset for Clustering.ipynb: Jupyter Notebook containing the code for data preprocessing, exploratory data analysis, and clustering using various algorithms.
README.md: This file.
## Clustering Algorithms

The following clustering algorithms will be explored in this project:

- K-Means Clustering
- EDA (Exploratory Data Analysis)
- Feature Scaling
- PCA (Principal Component Analysis)
- Cluster Visualization with Plotly
- Conclusion

The customer segmentation obtained from this project can be used by credit card companies to develop personalized marketing strategies and product offerings for different customer segments. Additionally, the insights gained from the clustering analysis can provide valuable information about customer behavior patterns and credit risk assessment.
