# Boston House Prices Prediction 

## Introduction
This repository contains an end-to-end analysis and solution to the [Boston House Prices Prediction](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices).
I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail
each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
The Boston House Price Prediction is one of the famous Machine Learning Regression problem.

In this challenge, we build a predictive model that answers the question: “What could be the Sales Price of a House in Boston?” using the housing data (ie Crime Rate in the Area, How old is the house, Percentage of Lower Status of the population living in the area, Is the house river bound, etc).

This is a regression problem in machine learning as we are predicting the sales price of the houses using the given attributes.

## Evaluation metric
The evaluation metric of this problem is the Root Mean Squared Error of the regression model. This is also known as RMSE.

## Data description

Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): 

1. CRIM: per capita crime rate by town
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX: nitric oxides concentration (parts per 10 million)
6. RM: average number of rooms per dwelling
7. AGE: proportion of owner-occupied units built prior to 1940
8. DIS: weighted distances to ﬁve Boston employment centers
9. RAD: index of accessibility to radial highways
10. TAX: full-value property-tax rate per $10,000
11. PTRATIO: pupil-teacher ratio by town
12. B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town
13. LSTAT: % lower status of the population
14. MEDV: Median value of owner-occupied homes in $1000s

We can see that the input attributes have a mixture of units. Here, the target variable is MEDV.

## Conclusion

The best model for this problem is XG Boost Regression with a Root Mean Squared Error (RMSE) value of 5.045.
