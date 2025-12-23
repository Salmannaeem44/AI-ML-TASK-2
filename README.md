# Stock Price Prediction using Linear Regression

## Overview
This project aims to predict the next day's closing price of a stock (e.g., Apple, AAPL) using historical stock data. The model uses a **Linear Regression** algorithm and leverages features such as **Open**, **High**, **Low**, and **Volume** of the stock to predict the target variable, which is the **Close** price for the next day.

This project demonstrates the use of **Time Series Data** handling, **Regression Modeling**, and **Visualization** to predict stock prices.

## Project Features
- Fetch historical stock data from **Yahoo Finance** using the `yfinance` library.
- Preprocess the data by shifting the close prices to predict the next day's closing price.
- Train a **Linear Regression** model to predict the stock’s future closing prices.
- Visualize the predicted vs. actual closing prices using **matplotlib**.
- Evaluate model performance using **Mean Squared Error (MSE)**.

## Prerequisites

Before running the code, ensure you have the following Python libraries installed:
- `yfinance` – for fetching stock data
- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `scikit-learn` – for model training and evaluation
- `matplotlib` – for visualization

You can install these libraries using `pip`:

```bash
pip install yfinance pandas numpy scikit-learn matplotlib
