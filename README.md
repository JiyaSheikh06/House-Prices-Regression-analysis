# House Price Prediction

This repository contains a project for predicting house prices using machine learning techniques. The project uses a dataset of house sales to build and evaluate multiple regression models and generate predictions.

## Project Overview

The project covers data cleaning, feature engineering, model building, and evaluation. It includes preprocessing pipelines for numerical and categorical data, and a range of regression models including linear, ensemble, and stacking methods.

## Technology Stack

- **Python**: Programming language used for data processing and model building.
- **Libraries**:
  - `pandas`, `numpy`, `scipy`: For data manipulation and statistical analysis.
  - `matplotlib`, `seaborn`: For data visualization.
  - `scikit-learn`: For machine learning models, preprocessing, and model evaluation.
  - `xgboost`, `catboost`, `lightgbm`: For advanced boosting algorithms.
- **Jupyter Notebook**: For interactive development and data exploration.

## Data

- **train.csv**: Training dataset with various features and target variable `SalePrice`.
- **test.csv**: Test dataset used to generate predictions.

## Steps

1. **Load Data**: Reads the `train.csv` and `test.csv` files.
2. **Data Cleaning**:
   - Identifies and handles missing values.
   - Removes outliers based on domain knowledge and statistical analysis.
3. **Feature Engineering**:
   - Creates new features such as `houseage`, `totalsf`, and `totalbaths`.
   - Drops less informative features.
4. **Data Preprocessing**:
   - Applies missing value imputation, feature scaling, and encoding.
5. **Model Building**:
   - Trains and evaluates multiple regression models:
     - **Linear Regression**
     - **Random Forest Regressor**
     - **XGBoost Regressor**
     - **Gradient Boosting Regressor**
     - **Voting Regressor**
     - **Stacking Regressor**
6. **Model Evaluation**:
   - Uses metrics like RMSE to evaluate model performance.
   - Performs hyperparameter tuning with GridSearchCV.
7. **Predictions**:
   - Generates predictions for the test dataset.
