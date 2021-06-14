# Credit_Risk_Analysis

## Table of Contents
* [Project title](#project-title)
* [Technologies](#technologies)
* [Overview](#overview)
* [Results](#results)
* [Summary](#summary)



## Project title
Credit Risk Analysis

## Technologies
[Python](https://www.python.org/downloads/ "Download Python") 3.7.9.

## Overview 
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. For this project, I applied machine learning to solve a real-world challenge: credit card risk. I employed different techniques to train and evaluate models with unbalanced classes:
* oversample the data using the RandomOverSampler and SMOTE algorithms;
* undersample the data using the ClusterCentroids algorithm;
* a combinatorial approach of over- and undersampling using the SMOTEENN algorithm;
* then, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

After evaluating the performance of these models and I was able to make a written recommendation on whether they should be used to predict credit risk.

## Results

### Oversampling
#### Naive Random Oversampling

![](img/NaiveRandomOversampling.png)

The accuracy score for the random oversampling is 0.65. The precision for high_risk is 0.01, very low and high for the low risk, indicating an overfitting for the low_risk. The recall (sensitivity) for both cases are not ideal.
