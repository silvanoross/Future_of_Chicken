# Title: Meat Predictor


# Group Members: David Hutsell, Saidee Padilla, Silvano Ross, Ryan Svendson
---

# Data Source: Kaggle: [4 Meat Price History](https://www.kaggle.com/datasets/chinmayshanbhag/historical-price-data-of-4-meats-commodity)
---

# Purpose: Create 1, 5 and 10 year predictions for chicken prices based on 20 years of historical monthly data to determine budgeting needs assuming we are a grocery store manager or to help plan a personal budget. To save the machine learning models as pickle files for future use.
---

# New Machine Learning Model: XGBoost
---

# Breakdown: 2 people will use the Prophet Model - David and Saidee,                                   2 people will use XGBoost - Ryan and Silvano

# Course of Action: 
>## 1. Create properly formatted dataframes of chicken prices for use in the Prophet and XGBoost Machine Learning models. Finding features for use in XGBoost and making sure data in 'DS' and 'Y' format for Prophet. 

>## 2. Display 1, 5 and 10 year predictions and evaluation of each model using Rsquared, MAPS score and MSE score

>## 3. Find the seasonality of prices, whether or not there is a significant change in prices depending on the time of year.

>## 4. Pickle both of our models for use in future predictions.

# Extras
Alert for futures trading in selected meat with respect to seasonality.

# Comments

need accuracy, how accurate are our predictions, 
Go back in time to test predictions
For 5 years, take 15 years as training and last 5 years as testing dataset
Metrics: R^2, maps score, mse score, - look at two are or three scores to determine which model is better
Orbit, gray kites, aws deep ar
Model - pickle a model after fit, dump into s3 bucket (boto3, aws SDK), load into lambda function, run .predict, use get_object api 

