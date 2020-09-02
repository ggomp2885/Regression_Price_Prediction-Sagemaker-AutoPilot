# AutoPilot_Price_Prediction-SagemakerS
This repository contains my project for using AWS Sagemaker Autopilot to predict the sale price of Boston homes. Using the Boston Housing Dataset from UCI.


## Files included in this repository and their use
Main Notebook.ipynb - JupiterNotebook containing all code used in project

housing.csv - the dataset used for the project

LICENSE - MIT license for this project

README - this file


## Main Notebook uses Python 3.6 and the following libraries
Pandas

Matplotlib

SKlearn

Numpy


# Project Overview
In this project, I will be able to predict the sale price of homes in Boston. 
I will be able to do this by using a data set of 14 measurements, recorded on 506 homes, by the UCI machine learning repository in 1978.
I will examine the relationships between these measurements, first with visualizations of these relationships, and then,, with multiple regression machine learning algorithms. I will use RMSE as my evaluation metric with 10-fold Cross Validation.  I will graph the results, and then I will hyperparameter tune the highest performing models, and finally, use an unseen test set of 20% of the data, to choose the highest performing model overall.

Link to Boston Housing Dataset:
https://www.kaggle.com/c/boston-housing
