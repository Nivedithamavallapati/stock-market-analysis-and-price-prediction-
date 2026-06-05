## Stock Market Analysis and Price Prediction

## Project Overview
This project focuses on analyzing historical stock market data and predicting future stock closing prices using Machine Learning techniques. It helps in understanding market trends and making data-driven financial decisions.


## Dataset Description
The dataset contains historical stock price information including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume


## Objective
To build a machine learning model that predicts the closing price of a stock based on historical data.


## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


##  Steps Performed

##  Data Collection
Loaded stock market dataset (CSV format).

##  Data Cleaning
- Handled missing values
- Converted date column to datetime format
- Sorted data in chronological order

##  Exploratory Data Analysis (EDA)
- Stock price trend visualization
- Moving average analysis
- Volume analysis
- Correlation heatmap
- Distribution of returns

##  Feature Engineering
Created new features:
- Month
- Year
- Day

##  Model Building
Used **Random Forest Regressor** to predict stock closing prices.

## Model Evaluation
Evaluated using:
- Mean Squared Error (MSE)
- R² Score

##  Results
- The model successfully predicts stock closing prices with reasonable accuracy.
- Visual comparison between actual vs predicted values shows good alignment.


##  Visualizations
- Stock Price Trend Graph
- Moving Average Plot
- Daily Returns Distribution
- Volume Analysis
- Actual vs Predicted Graph

## Insights
1.Stock prices follow strong trends over time
2.Moving averages help identify market direction
3.Volume impacts price movement
4.Random Forest gives decent prediction accuracy
