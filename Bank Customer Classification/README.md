# Classification Of Bank Customers
## Portugal Bank Marketing dataset.



## Table Of Content 
* [Overview](#overview)
* [Motivation](#motivation)
* [Technical Aspect](#technical-aspect)
* [Results](#results)


## Overview
Given is the ‘Portugal Bank Marketing’ dataset , Containing different features . All the features are categories in the 'Bank client data', 'Related with the last contact of the current campaign' , Other attributes' , 'Social and economic context attributes' sections.Depend upon all this features classifying the customer to the class of if they are subscribed to term deposite "yes" or "No".


## Motivation

A Classification model is alaways a good machine learning problem. To create a model based on classification I choosed this problem Statement.

 

## Technical Aspect
* This Notebook contains supervised machine learning model for classification problem.
* The Models in Python as scripting langauge are :
    - Logistic Regression (Statsmodels library,sklearn Library)
    - AdaBoost (sklearn Library)
    - Naïve Bayes (sklearn Library)
    - KNN (sklearn Library)
    - SVM (sklearn Library)
* For Feature Selection the following technique used :
    - Random Forest Classifier (Sklearn library)
* Data Distribution balencing done by :
    - SMOTE
* For Data standerdizing the following methods used (from sklearn library):
    - Standerd Scaler
    - Minmax Scaler

## Results
    
|Models|Accuracy|
|-------|--------------------|
|Logit|0.868804|
|Logistic|0.881299|
|Naive Bayes|0.783437|
|KNN|0.918464|
|SVM Classifier|0.883032|
|Adaboost (DT)|0.935610|
|Adaboost (Logistic)|0.850290|

<b>The results From Adaboost and KNN gives better model prediction than the other models</b>

