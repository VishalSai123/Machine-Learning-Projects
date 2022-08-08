# Titanic: Machine Learning from Disaster 

## Introduction
This repository contains an end-to-end analysis and solution to the [Kaggle Titanic survival prediction competition](https://www.kaggle.com/competitions/titanic). I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

This is a binary classfication problem in machine learning as we are classifying the outcomes of passengers as either survived or did not survive the Titanic.

## Evaluation metric
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by our model. This is known as accuracy.

## Data description

In this competition, you’ll gain access to two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled `train.csv` and the other is titled `test.csv`.

Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.

The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.

Using the patterns you find in the train.csv data, predict whether the other 418 passengers on board (found in test.csv) survived.

Below are the description of the features in the data:
- Survival: 0 = Did not survive, 1 = Survived
- Pclass: Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.
- Sex: Male or female
- Age: Age in years, fractional if less than 1
- SibSp: Number of siblings or spouses aboard the titanic
- Parch: Number of parents or children aboard the titanic
- Ticket: Passenger ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton

## Conclusion

The best model for this problem is Stacking Classifier with a test accuracy of 78.468 percent.
