# Breast Cancer Detection - Wisconsin Breast Cancer Dataset

## Introduction
This repository contains a machine learning approach and solution to the [Breast Cancer Detection](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset). I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign (non cancerous). A benign tumor has distinct, smooth, regular borders. A malignant tumor has irregular borders and grows faster than a benign tumor. A malignant tumor can also spread to other parts of your body. A benign tumor can become quite large, but it will not invade nearby tissue or spread to other parts of your body.

This is a binary classfication problem in machine learning as we are detecting whether a person has Breast Cancer or not.

## Evaluation metric
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by our model. This is known as accuracy.

## Data description
This data was donated by researchers of the University of Wisconsin and includes the measurements from digitized images of fine-needle aspirate of a breast mass.

The breast cancer data includes 569 examples of cancer biopsies, each with 32 features. One feature is an identification number, another is the cancer diagnosis and 30 are numeric-valued laboratory measurements.
The diagnosis is coded as "M" to indicate malignant or "B" to indicate benign.

The other 30 numeric measurements comprise the mean, standard error and worst (i.e. largest) value for 10 different characteristics of the digitized cell nuclei, which are as follows:-

1. Radius
2. Texture
3. Perimeter
4. Area
5. Smoothness
6. Compactness
7. Concavity
8. Concave Points
9. Symmetry
10. Fractal dimension

## Conclusion
The best model for this project is Stacking Classifier with a model accuracy of 98.25 percent, a model recall of 95.56 percent, and a validation accuracy of 97.6 percent.
