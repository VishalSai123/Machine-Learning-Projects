# Credit Card Customer Segmentation using Clustering and Analysis 

## Introduction
This repository contains an analysis and solution to the [Credit Card Customer Data](https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data). 
I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. 
This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem context
A Customer Credit Card Information Dataset which can be used for Identifying Loyal Customers, Customer Segmentation, 
Targeted Marketing and other such use cases in the Marketing Industry.

A few tasks that can be performed using this dataset are as follows:

1. Perform Data-Cleaning, Preprocessing, Visualizing, and Feature Engineering on the Dataset.
2. Implement Hierarchical Clustering and K-Means Clustering models.
3. Create RFM (Recency, Frequency, Monetary) Matrix to identify Loyal Customers.

## Data description
The dataset consists of 7 columns:

1. Sl_No: Customer serial identification number (serves the purpose of indexing values).
2. Customer Key: Customer key
3. Avg_Credit_Limit: Average credit card limit for the customer
4. Total_Credit_Cards: Total credit cards owned by the customer
5. Total_visits_bank: Total number of bank visits by the customer
6. Total_visits_online: Total visits online by the bank customer
7. Total_calls_made: Total calls made by the customer to the bank

## Conclusion
The best model for this problem is the K-Means clustering algorithm with a better Silhouette Score of 0.73 and Calinski Harabasz score of 3254.49 than Hierarchial Clustering. 
We also identified Top customers using the RFM (Recency, Frequency, Monetary) matrix.
