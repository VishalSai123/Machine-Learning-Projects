# Credit Score Classification 

## Introduction
This repository contains an end-to-end analysis and solution to the [Credit Score Classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification). I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
You are working as a data scientist in a global finance company. Over the years, the company has collected basic bank details and gathered a lot of credit-related information. The management wants to build an intelligent system to segregate the people into credit score brackets to reduce the manual efforts.

Given a person’s credit-related information, build a machine learning model that can classify the credit score.

## Evaluation metric
The evaluation metric of this dataset is the percentage of customer's data in the test set that are correctly predicted by our model. This is known as accuracy. Similarly, we also focus on metrics like precision and recall.

## Data description

In this competition, you’ll gain access to two similar datasets that include customer information like name, age, occupation, annual income, monthly inhand salary, etc. One dataset is titled `train.csv` and the other is titled `test.csv`.

Train.csv will contain the details of a subset of the customers and importantly, will reveal whether their credit score is poor, standard, and good,also known as the “ground truth”.

The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each customer. It’s your job to predict these outcomes.

Using the patterns you find in the train.csv data, predict whether the credit score of the customers in the test.csv data is either poor, standard, and good.

## Conclusion:
The best model for this problem is Stacking Classifier with a model accuracy of 81.02 percent, a model precision of 80.98 percent, and a model recall of 81.02 percent.
