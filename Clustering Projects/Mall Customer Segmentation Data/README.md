# Mall Customer Segmentation Data 

## Introduction
This repository contains an analysis and solution to the [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.
Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

## Data description
This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis.
I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm and Hierarchial Clustering Algorithm) in the simplest form.

The dataset consists of 5 columns:

1. CustomerID: Unique ID assigned to the customer
2. Gender: Gender of the customer
3. Age: Age of the customer
4. Annual Income (k$): Annual Income of the customer
5. Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature

## Conclusion
The best model for this problem is K-Means clustering algorithm with a better Silhouette Score and Calinski Harabasz score than Hierarchial Clustering.
