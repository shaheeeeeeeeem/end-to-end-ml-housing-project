# Housing ML Project

An end-to-end machine learning project for predicting housing prices using the California housing dataset.  
This project covers the complete ML workflow: data loading, exploration, preprocessing, model training, hyperparameter tuning, and final evaluation.

## Project Overview

The goal of this project is to build a regression model that predicts median house values based on features such as location, income, population, number of rooms, and housing age.

The final model uses a complete Scikit-learn pipeline with preprocessing and a Random Forest Regressor.

## What I Did

- Loaded and explored the housing dataset
- Performed train-test splitting
- Used stratified sampling for better dataset representation
- Visualized geographical housing data
- Studied correlations between features and the target value
- Created new useful features using custom transformations
- Handled missing values
- Applied feature scaling
- Encoded categorical variables using one-hot encoding
- Built preprocessing pipelines using Scikit-learn
- Trained multiple models
- Used GridSearchCV / RandomizedSearchCV for hyperparameter tuning
- Evaluated the final model on the test set

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Final Result

The best model was a Random Forest Regressor with preprocessing included in the pipeline.

Final test RMSE:

```text
41974.22
