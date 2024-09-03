## Boston Housing Price Prediction
# Overview

This repository contains a Jupyter Notebook implementing a machine learning model to predict housing prices in Boston using the well-known Boston Housing dataset. The model is built using various regression techniques to analyze and predict the prices based on a set of features.

# Dataset

The dataset used in this project is the Boston Housing Dataset, which contains 506 samples and 14 feature variables. These features include:

CRIM: Per capita crime rate by town

ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.

INDUS: Proportion of non-retail business acres per town

CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)

NOX: Nitric oxide concentration (parts per 10 million)

RM: Average number of rooms per dwelling

AGE: Proportion of owner-occupied units built before 1940

DIS: Weighted distances to five Boston employment centers

RAD: Index of accessibility to radial highways

TAX: Full-value property tax rate per $10,000

PTRATIO: Pupil-teacher ratio by town

B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black people by town

LSTAT: Percentage of lower status of the population

MEDV: Median value of owner-occupied homes in $1000s (Target variable)

# Project Structure

Boston_Housing_Price_Prediction.ipynb: The Jupyter Notebook containing the entire code for data exploration, preprocessing, model building, and evaluation.

README.md: This file, providing an overview of the project.

Boaton_housing.csv:  A csv file containing the dataset over which the model has been developed.

# Usage

The notebook guides you through the following steps:

1. Data Loading: Load the Boston Housing dataset.

2. Exploratory Data Analysis (EDA): Understand the data distribution and relationships between variables.

3. Data Preprocessing: Handle missing values, feature scaling, and data splitting.

4. Model Building: Implement multiple regression models, including Linear Regression, Ridge, Lasso, and Random Forest Regressor.

5. Model Evaluation: Evaluate the models using metrics such as Mean Squared Error (MSE) and R² score.

6. Prediction: Use the trained model to predict housing prices.

# Results

The final section of the notebook presents the model's performance on the test set.
