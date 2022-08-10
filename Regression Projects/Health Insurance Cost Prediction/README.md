# Health Insurance Cost Prediction 

## Introduction
This repository contains an end-to-end analysis and solution to the [Health Insurance Cost Prediction](https://www.kaggle.com/datasets/annetxu/health-insurance-cost-prediction).
I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail
each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
The Health Insurance Cost Prediction is one of the famous Machine Learning Regression problem.

In this challenge, we build a predictive model that answers the question: “What could be the Health Insurance Cost of an individual?” 
using the customers data (i.e., Age of the customer, Sex of the customer, Region of the customer, Does the customer smoke?, etc).

This is a regression problem in machine learning as we are predicting the health insurance cost using the given attributes.

## Evaluation metric
The evaluation metrics for this problem is the Root Mean Squared Error (also known as RMSE) and R-squared value of the regression model.

## Data description

Each record in the database describes a customer. The attributes are defined as follows:

1. Age
2. Sex
3. BMI
4. Children
5. Smoker
6. Region
7. Charges

We can see that the input attributes have a mixture of units. Here, the target variable is Charges.

## Conclusion

The best model for this problem is Random Forest Regression with a Root Mean Squared Error (RMSE) value of 5369.37 and an R-squared value of 0.8.
