# House Price Predictor

## Overview
A Machine learning project predicting the house prices using neighborhood and house utilities features.\
Built using numpy, pandas, matplotib and scikit learn

## Key Finding
The EDA and feature engineering took quite a lot of time since this data was quite messy with roughly 80 features, but that's what makes real projects FUN 😉

I used 3 different models to predict the house prices - Linear Regression, Random Forests and XGBoost.

- Linear Regression got RMSE as $ 25,000 and R2 score of 91.5% on the training dataset (train.csv), but on the testing dataset (test.csv) the result was 85%
- Random Forest didn't have much difference compared to linear regression, it got 89% R2 score on the training data and same 85% on the testing data
- XGBoost was the model that performed the best among the three. It achieved a score of 92% on the training dataset and 87.2% on the testing data

## Tech Stack
- Python, Numpy, Pandas, matplotlib
- Scikit-learn (Linear Regression, Random Forest, XGBoost)

## Models Compared
Model &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Train &emsp; Test\
Linear Regression &emsp;  91.5%   &emsp;   85.0%\
Random Forest    &emsp;&emsp;&nbsp;   89.0%   &emsp;   85.0%\
XGBoost         &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;    92.0%   &emsp;   87.2%

## Dataset used
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
