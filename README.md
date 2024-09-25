Bike-Sharing Demand Prediction Project
Table of Contents

General Info
Technologies Used
Features
Setup
Usage
Project Status
Room for Improvement
Acknowledgements

# General Information

This project aims to build a multiple linear regression model to predict the demand for shared bikes.
The project is based on data from a US bike-sharing provider, BoomBikes, which has experienced revenue declines due to the COVID-19 pandemic.
The goal is to understand the factors affecting bike demand and how these factors will impact the business once the pandemic subsides.
The dataset used contains daily bike demands across the American market based on various meteorological surveys and people's styles.

# Technologies Used

Python - version 3.12
pandas - version 2.2.3
numpy - version 2.1.1
scikit-learn - version 1.5.2
matplotlib - version 3.9.2
seaborn - version 0.13.2

# Features

Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Feature selection using Recursive Feature Elimination (RFE)
Multiple Linear Regression modeling
Model evaluation and interpretation

# Setup
To run this project, install the required libraries using pip:
Copypip install pandas numpy scikit-learn statsmodels matplotlib seaborn
Usage

Ensure the 'day.csv' dataset is in the same directory as the Jupyter notebook.
Run the Jupyter notebook cells sequentially to perform data preprocessing, EDA, model building, and evaluation.

# Project Status
Project is: Completed

Address multicollinearity issues in the model
Explore non-linear relationships between variables
Implement more advanced feature selection techniques

# To do:

Perform cross-validation for more robust model evaluation
Experiment with other regression techniques (e.g., Ridge, Lasso)
Create a user-friendly interface for making predictions

# Acknowledgements

This project was inspired by the need to understand post-pandemic market dynamics in the bike-sharing industry.
Many thanks to BoomBikes for providing the dataset and problem statement.

# Contact 
Created by [@alphaabhi] - feel free to contact me!
Abhinav Jha
