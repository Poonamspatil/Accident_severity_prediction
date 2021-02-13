# Accident Severity Prediction
The project explores different machine learning techniques for binary classification to predict accident severity. Classification is performed using Gaussian Naive Bayes, Support Vector machine (SVM) and Neural Network algorithms.

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Description](#description)
* [Results](#results)

## Introduction
It explores different Machine Learning algorithms to predict severity of an accident given different features. The project predicts how different features like weather conditions, vehicle category, speed limit, time of day etc impact severity of an accident. Accident severity prediction can provide crucial information for emergency responders to evaluate the severity level of accidents, estimate the potential impacts, and implement efficient accident management procedures.

## Technologies
Project is created with:
* Python : 3.7

## Description
The project goal is to build a classification model to predict the Accident Severity for road accidents in UK. In particular, the notebook demonstrates 3 classifiers for data modeling using Naive Bayes, SVM and Neural Network for the task and uses multiple corresponce analysis (MCA) as dimension reduction technique.

Data: Road accidents in UK between 2010 and 2014 Link: https://www.kaggle.com/stefanoleone992/adm-project-road-accidents-in-uk Dataset: 75550 x 33 Response: 0 - Slight and 1 - Fatal-Serious

Part 1 - Feature Engineering: Data exploration, stratefied sampling for create train-test set, dimension reduction using Multiple correspondence analysis MCA and feature selection are  implemented.

Part 2 - Data modeling: Different machine learning algorithm applied to perform binary classification. K-fold cross validation is used for model validation and hyper parameter tuning. Classifier algorithm explored are:
1. Naives Bayes classifier
2. Neural network classifier
3. Support vector machine 

## Results
Evaluation metric used: Accuracy

SVM : 0.7575571
Neural Network : 0.7558714
Naive Bayes : 0.7527714 

Amongst the classifiers, GaussianNB, poly SVM and Shallow Neural Network classifiers, although comparable but SVM algorithm yields best results overall based on the accuracy metrics. Therefore, the project demonstrates that using these classification methods can be a useful tool to classify accident severity.
