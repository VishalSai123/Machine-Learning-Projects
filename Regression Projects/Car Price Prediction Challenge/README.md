# Car Price Prediction Challenge 

## Introduction
This repository contains an end-to-end analysis and solution to the [Car Price Prediction Challenge](https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge).
I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail
each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
The Car Price Prediction Challenge is one of the famous Machine Learning Regression problem.

In this challenge, we build a predictive model that answers the question: “What could be the Sales Price of a Car?” using the car data (i.e., Manufacturer, Fuel type, Mileage, Cylinders, Wheel, Doors, Airbags, etc).

This is a regression problem in machine learning as we are predicting the sales price of a car using the given attributes.

## Evaluation metric
The evaluation metric of this problem is the Root Mean Squared Error (also known as RMSE) nd R-squared of the regression model.

## Data description

Each record in the database describes a Car. The dataset consists of 19237 rows x 18 columns. The attributes are deﬁned as follows: 

1. ID: A counter variable, unique for every record.
2. Price: Price of the car.
3. Levy: Levy on the car
4. Manufacturer: Manufacturer of the car
5. Model: Model name of the car
6. Prod. year: Production year of the car
7. Category: What category is that car
8. Leather interior: Does the car have a leather interior or not
9. Fuel type: Which type of fuel does the car use
10. Engine volume: Engine capacity of the car
11. Mileage: Mileage of the car
12. Cylinders: No. of cylinders in the car
13. Gear box type: Gear box type of the car
14. Drive wheels: What type of drive wheels are there for the car
15. Doors: No. of doors in the car
16. Wheel: Position of steering in the car
17. Color: Color of the car
18. Airbags: No. of airbags in the car

We can see that the input attributes have a mixture of units. Here, the target variable is Price.

## Conclusion

The best model for this project is Random Forest Regression (1000 trees) with a Root Mean Squared Error (RMSE) value of 10.043 and an R-squared value of 0.661.
