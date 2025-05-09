# car-price-prediction


This project focuses on predicting the prices of used cars using machine learning techniques. By analyzing a dataset containing various features of used vehicles, the model aims to estimate car prices with high accuracy, helping both buyers and sellers make data-informed decisions.

## Project Overview

The project involves:
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering
- Model training and evaluation
- Price prediction using supervised learning algorithms

## Dataset

The dataset includes features such as:
- Make and model
- Year of manufacture
- Mileage
- Engine size
- Transmission type
- Fuel type
- Number of doors
- Tax and MPG
- Price (target variable)

(Data source: [https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho]

## Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for visualization
- Scikit-learn for modeling and evaluation

## Models Applied

- Linear Regression, Lasso
- KNN
- Random Forest
- Gradient Boost
- XGBoost
- SVM
- GridSearchCV for hyperparameter tuning

## Results

- Best model performance: [Gradient Boosting, RMSE:129639.022]
- Feature importance analysis shows that [ "age" and "Max_power"] are the most significant predictors of price.
