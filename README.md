# House Price Prediction with Deep Learning

This notebook using python for deep learning and data science in attempt to predict the house price based on the attributes.

## Problem

Given a data about house price (dependent variable) and other features (independent variables) and We guess the house price.

## About the Data

Get the data for house price prediction from Kaggle. Here is the link: https://www.kaggle.com/datasets/samuelcortinhas/house-price-prediction-seattle

## Evaluation

The evaluation metrics is mean absolute error (`MAE`) for loss function.

## Result

Succesfully to handle overfitting with add more data for training. Then, This project also successfully get the best model with loss function score is 96,000 than other models that we have created

## Workflow of this project
* Preparing the data (Loading from Kaggle, explore the data for getting insights, preprocessing the data like handle missing values, duplicated, one hot, and feature scaling, and split the data into 2 sets (training, validating) for the small datasets. Then, training using full datasets from `train.csv` and testing using data from `test.csv.
* Build the deep learning model (simple NN model)
* Monitoring the performance of loss and metrics for each training sets and testing sets
* Improve the model (Using tuning the hyperparameter)
* Save the model
