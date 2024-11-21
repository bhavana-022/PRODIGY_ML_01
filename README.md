# PRODIGY_ML_01
TASK-1: Linear Regression Model for House Price Prediction
Problem Statement
The goal of this task is to implement a Linear Regression Model to predict house prices based on the following features:

Square footage
Number of bedrooms
Number of bathrooms
This project provides a foundation for understanding regression analysis and developing a machine learning model to solve real-world prediction problems.

Data
Description
The dataset used in this project contains information on 128 houses, with the following features:

Price: The selling price of the house (target variable).
SqFt: Square footage of the house.
Bedrooms: Number of bedrooms.
Bathrooms: Number of bathrooms.
Offers: Number of offers received for the house.
Brick: Whether the house has brick construction (Yes or No).
Neighborhood: The location of the house (East, North, or West).

Setup and Requirements
Prerequisites
Python 3.8+
Libraries:
pandas
numpy
matplotlib
scikit-learn

Preprocessing Steps
Before feeding the dataset to the machine learning model, the following preprocessing steps are performed:

Handle Categorical Data:
Convert Brick and Neighborhood to numerical values using one-hot encoding or label encoding.
Feature Scaling:
Scale continuous features like SqFt, Bedrooms, Bathrooms, and Offers for better model performance.
Train-Test Split:
Split the data into training and testing sets.
Sample Rows from the Dataset
Home	Price	SqFt	Bedrooms	Bathrooms	Offers	Brick	Neighborhood
1	114300	1790	2	2	2	No	East
2	114200	2030	4	2	3	No	East
3	114800	1740	3	2	1	No	East
4	94700	1980	3	2	3	No	East
5	119800	2130	3	3	3	No	East
For a complete dataset, refer to the provided file: house_prices.csv

Model Implementation
Steps
Data Preparation:

Clean and preprocess the dataset.
Handle missing values, if any.
Normalize/standardize the data, if necessary.
Model Training:

Train a Linear Regression model using scikit-learn.
Model Evaluation:

Evaluate the model using the test dataset.
Calculate performance metrics like MAE, MSE, and R² Score.
Visualization:

Plot the predicted vs actual prices.
