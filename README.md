# EE8603 Final Project - Abalone Regression
## Created by: Brendan Wood - November 29, 2023
This repository is Brendan Wood's final project submission for EE8603.

## About the Project
The code in this repository uses PyCaret to perform a linear regression on the [Abalone dataset](https://archive.ics.uci.edu/dataset/1/abalone). The program then saves the best performing model and illustrates some parameters and metrics of the model.

## Running Instructions
The preferred method for running this notebook is in Google Collab. All cells should be excecuted in order.

## Abstract
Linear regression is one of the most widely used machine learning algorithms for prediction of a continuous variable. Since its introduction in the early 19th century, there have been numerous innovations upon the originally proposed algorithm such as ridge regression, LASSO regression and many others. The purpose of this work was to investigate which permutation of linear regression would be most effective at predicting the age of Abalone marine snails from physical measurements of the snails. The results of this work show that after 5-fold cross validation, a Gradient Boosting Regressor was best fit to predict the age of the Abalone with an average Mean Squared Error, normalized by the variance of the output space, of 0.454, followed by a Random Forest Regressor and a Light Gradient Boosting Machine. 

## Link to Video
A video description of this project and it's findings can be found [here](https://youtu.be/-5llh01FI_Y).
