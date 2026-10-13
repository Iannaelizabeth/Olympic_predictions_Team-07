# Olympic Medal Prediction Using Machine Learning

## Overview
This project reproduces and extends a research project on predicting Olympic medal counts using machine learning. It uses country-level Olympic data and socioeconomic indicators to predict the total medals won by each country.

## Models Used
**Classification:**
- Logistic Regression
- Support Vector Machine (SVM)
- Gaussian Naive Bayes (GNB)
- Multi-Layer Perceptron (MLP)
- Random Forest Classifier

**Regression:**
- Linear Regression
- Ridge and Lasso Regression
- Poisson Regression
- Support Vector Regression (SVR)
- Random Forest Regressor
- Weighted Linear Regression

## Extension
Negative Binomial Regression was added to investigate whether modelling overdispersion in medal counts could improve predictions. However, it did not outperform the GNB + SVR pipeline.

## Best Result
The GNB + SVR pipeline achieved a test RMSE of **2.747** on the 2016 Olympic data.

## Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels.

## Dataset
Olympic athlete/event records and World Bank socioeconomic indicators.

## Key Finding
A model that accounts for overdispersion does not necessarily produce more accurate predictions. Model performance must be evaluated using validation and test data.
