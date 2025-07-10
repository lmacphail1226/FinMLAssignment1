# FinMLAssignment1

## Description
Assignment 1 is a classification model designed to predict the likelihood of a stock going up or down the following day. Draft Kings (DKNG) stock was used as the stock for this model

## How to Use
The following modules were used in the Jupyter Notebook and will be required to be able to run the notebook.
* numpy: 1.26.4
* pyarrow: 17.0.0
* polars: 1.31.0
* seaborn: 0.13.2
* sklearn: 1.4.2
* scipy: 1.15.3
* yfinance: 0.2.64
* xgboost: 3.0.0
* lightgbm: 4.6.0

The Notebook will execute 4 different models (Logistic, SVM, XGBoost, and Light GBM) starting with a baseline model and then using a randomized search to find the optimal hyperparameters. The notebook is set up with the correct hyperparameters given the random state selected (2025), but hyperparameters may need to be updated if the random state is updated

Final output is a ROC and Precision Recall curve for each of the fitted models
