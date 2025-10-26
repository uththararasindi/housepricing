# housepricing
California House Price Prediction | Random Forest Regressor

This repository contains a machine learning project for predicting California house prices using a Random Forest Regression model. The project covers data preprocessing, model training, evaluation, and prediction.

--Project Overview--

The goal of this project is to predict the median house value in California based on features such as location, housing age, income, and more.

The workflow includes:

Data Preprocessing: Handling missing values, outlier detection, feature creation, encoding categorical variables, normalization, and feature selection.

Model Training: Implemented a Random Forest Regressor and tuned hyperparameters using GridSearchCV.

Evaluation: Measured performance using R², RMSE, MAE, and 10-fold cross-validation.

Prediction Interface: Built a simple user input system for predicting house prices based on numeric and categorical features.

The trained Random Forest model achieved strong performance on the test data and was compared against other regression models like Linear Regression, Lasso, Decision Tree and Extra Trees.

Metrics:

R² Score: 0.681

RMSE: 52722.491 

MAE: 37765.454


--Tech Stack--

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Joblib
