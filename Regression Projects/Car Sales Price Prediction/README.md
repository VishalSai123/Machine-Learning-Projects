# Car Sales Prices Prediction 

## Introduction
This repository contains an end-to-end analysis and solution to the [Car Sales Price Prediction](https://www.kaggle.com/datasets/gagandeep16/car-sales).
I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail
each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
The Car Sales Price Prediction is one of the famous Machine Learning Regression problem.

In this challenge, we build a predictive model that answers the question: “What could be the Sales Price of a Car?” using the cars data (i.e., Car Manufacturer, Sales in thousands, Year resale value, Price in thousands, Engine size, Horsepower, etc).

This is a regression problem in machine learning as we are predicting the sales price of the cars using the given attributes.

## Evaluation metric
The evaluation metrics for this problem is the Root Mean Squared Error (also known as RMSE) and R-squared value of the regression model.

## Data description

Each record in the database describes a Car. This data set is being taken from the Analytixlabs for the purpose of prediction. The attributes are defined as follows:

1. Manufacturer
2. Model
3. Sales in thousands
4. Year resale value
5. Vehicle type
6. Price in thousands
7. Engine size
8. Horsepower
9. Wheelbase
10. Width
11. Length
12. Curb weight
13. Fuel capacity
14. Fuel efficiency
15. Latest Launch 
16. Power performance factor

We can see that the input attributes have a mixture of units. Here, the target variable is Price in thousands.

## Conclusion

The best model for this problem is Linear Regression with a Root Mean Squared Error (RMSE) value of 4.245 and an R-squared value of 0.926.
