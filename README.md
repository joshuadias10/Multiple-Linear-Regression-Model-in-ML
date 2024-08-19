# Multiple Linear Regression Model

This repository contains an implementation of a Multiple Linear Regression model using machine learning techniques in Python. The model is designed to predict sales based on advertising budgets across different media channels.

## Overview

In this practical, we utilized a machine learning approach to develop a Multiple Linear Regression model using the `company.csv` dataset. The dataset contains information on advertising budgets for TV, Radio, and Newspaper, along with corresponding sales figures. The goal is to predict sales based on these advertising expenditures.

## Steps Included

1. **Data Loading and Exploration**:
   - Load the dataset using `pandas`.
   - Inspect the data structure and check for any inconsistencies or missing values.

2. **Feature Selection**:
   - Identify the features (`TV`, `Radio`, `Newspaper`) and the target variable (`Sales`).

3. **Data Splitting**:
   - Split the data into training and testing sets to evaluate the model's performance.

4. **Model Training**:
   - Train the Multiple Linear Regression model using the training data with the `LinearRegression` class from the `scikit-learn` library.

5. **Predictions**:
   - Generate predictions on the test set using the trained model.

6. **Model Evaluation**:
   - Assess the model's accuracy using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R-squared score (`r2_score`).

7. **Visualization**:
   - Visualize the relationship between advertising spends and sales through scatter plots.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib

## Conclusion

This project illustrates how machine learning can be used to build and evaluate a Multiple Linear Regression model, providing insights into the relationship between different variables and their collective impact on the target outcome.
