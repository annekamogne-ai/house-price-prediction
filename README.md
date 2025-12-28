HOUSE PRICE PREDICTION – Data Analysis & Regression Models

This project is part of the Data Analysis with Python course offered by IBM on Coursera.
The goal is to analyze a housing dataset, perform exploratory data analysis (EDA), build multiple regression models, and compare their performance on the test set.

 PROJECT OVERVIEM

The project focuses on understanding the key factors that influence house prices and evaluating different machine learning models to predict the final price.

 STEPS AND METHODOLOGY
1. Importing Required Libraries

The analysis was performed using:

pandas for data manipulation

numpy for numerical processing

matplotlib & seaborn for visualization

sklearn for model building and evaluation

2. Data Cleaning and Preparation

Checked data types of each column

Removed irrelevant or redundant features

Handled missing values by replacing them with the column mean

Detected outliers using boxplots

3. Exploratory Data Analysis (EDA)

Visualizations were used to understand relationships between predictors and the target variable:

Boxplots for distribution and outlier detection

Regression plots (regplots) to investigate linear relationships

These steps helped identify the most relevant variables for modelling.

4. Machine Learning Models

Four regression models were trained and evaluated on the test set:

Model	Test Score
Simple Linear Regression	49%
Multiple Linear Regression	65%
Polynomial Regression (degree 2, with Pipeline)	75%
Ridge Regression	64%
5. Final Model Choice

The Polynomial Regression model (degree 2) performed the best on the test set with a score of 75%, making it the final chosen model.

 CONCLUSION

This project demonstrates:

Ability to clean and prepare real-world data

Understanding of EDA

Ability to compare multiple regression models

Use of Pipeline and regularization techniques

Model evaluation using training and test datasets
