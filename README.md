# **House Price Prediction ML Model**
This repository contains a machine learning model that predicts house prices using the Boston Housing Dataset (Boston.csv). The model uses features like the number of rooms, crime rate, property tax, and other housing attributes to estimate the price of houses in Boston.

## **Table of Contents**
- Dataset
- Features
- Model
- Evaluation

## **Dataset**
The dataset used is Boston.csv, which contains housing data collected from Boston, USA. The dataset includes features related to the properties, environment, and demographics of the area.
**Example of columns:**
- CRIM – per capita crime rate by town
- ZN – proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS – proportion of non-retail business acres per town
- RM – average number of rooms per dwelling
- AGE – proportion of owner-occupied units built prior to 1940
- TAX – full-value property tax rate per $10,000
- MEDV – median value of owner-occupied homes in $1000s (target)

## **Features**
The model uses numerical features such as:
- Crime rate (CRIM)
- Average number of rooms (RM)
- Property tax (TAX)
- Pupil-teacher ratio (PTRATIO)
- And other relevant housing and demographic features

## **Model**
The project implements two regression models:
- Linear Regression – baseline model to predict house prices.
- Random Forest Regressor – ensemble model for improved accuracy and higher R² score.
**Libraries Used:**
- pandas – Data manipulation
- numpy – Numerical computations
- scikit-learn – ML algorithms and evaluation
- matplotlib / seaborn – Data visualization

## **Evaluation**
The models are evaluated using metrics like:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
> The Random Forest Regressor usually provides a higher R² score than Linear Regression due to its ensemble nature.
