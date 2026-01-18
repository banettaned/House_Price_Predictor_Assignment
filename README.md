# House Price Prediction using Regularized Linear Regression

> This project predicts house prices using Linear Regression, Ridge Regression, and Lasso Regression, with a focus on regularization and feature selection.

## Objective
The objective of this project is to develop accurate and reliable models for predicting house prices using advanced linear regression techniques. By applying regularization methods, the project aims to improve model performance, prevent overfitting, and identify the most important features influencing house prices.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project analyzes a housing dataset to predict the sale price of houses.
- The main goal is to build robust and generalizable regression models that can accurately estimate house prices based on various features.
- The business problem addressed is to help stakeholders (buyers, sellers, and real estate agents) understand which factors most influence house prices and to provide reliable price predictions.

## Conclusions
- Data cleaning steps, including handling missing values and removing duplicates, are crucial for building robust predictive models.
- Regularization using Ridge and Lasso Regressions helps prevent overfitting and improves model generalization compared to standard linear regression.
- Lasso regression can perform feature selection by setting less important coefficients to zero, making the model simpler and more interpretable.
- The most important features for predicting house prices include overall quality, total square footage, and location-related variables.
- Doubling the regularization parameter (alpha) further shrinks coefficients, making the model simpler but potentially less accurate if over-regularized.
- Cross-validation is essential for selecting optimal hyperparameters and ensuring that the model generalizes well to unseen data.

## Technologies Used
- Python 
- pandas 
- numpy 
- scikit-learn 
- matplotlib 
- seaborn 

## Acknowledgements
- This project was based on standard machine learning workflows and tutorials for regularized regression and part of Upgrad Learning Assignment

## Contact
Created by [@banettned] - feel free to contact me!