Gold Price Prediction

Overview:

This repository contains code and resources for predicting the price of gold using machine learning techniques. The project aims to forecast future gold prices based on historical data.

Dataset ;

The dataset used for this project consists of historical gold prices from January 1, 2016, to December 21, 2021. Each observation includes the date and the corresponding gold price in USD per ounce.

Approach:

Data Exploration: Exploratory data analysis (EDA) will be performed to understand the distribution of gold prices over time and identify any trends or patterns.

Feature Engineering: Additional features may be derived from the date column, such as day of the week, month, or year, to improve model performance.

Stationary Check: Before modeling, it's essential to check if the time series data is stationary. This can be done visually by plotting the data and observing trends, or statistically using tests like the Augmented Dickey-Fuller (ADF) test.

Model Selection: Several machine learning algorithms will be evaluated for their ability to predict gold prices. Algorithms considered may include Linear Regression, Random Forest, and Gradient Boosting.

Model Training and Evaluation: The selected model will be trained on historical data and evaluated using metrics such as mean squared error (MSE) and mean absolute error (MAE) on a holdout test dataset.

Model Deployment: Once the model demonstrates satisfactory performance, it will be deployed for real-time predictions.

Files:

gold_price_prediction.ipynb: Jupyter Notebook containing code for data preprocessing, model training, and evaluation.

data/gold_price_data.csv: CSV file containing the historical gold price data.

gp.py: Python script for deploying the trained model for real-time predictions.
