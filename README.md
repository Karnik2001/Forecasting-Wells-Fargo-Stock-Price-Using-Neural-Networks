# 📈 Forecasting Wells Fargo Stock Price Using Neural Networks

This project focuses on forecasting the stock price of Wells Fargo (WFC) using deep learning techniques, specifically LSTM (Long Short-Term Memory) neural networks. The objective is to build a predictive model that captures the temporal dependencies in financial time series data to estimate future stock prices.
🔍 Project Overview

    Goal: Forecast Wells Fargo (WFC) stock prices using historical stock data and neural network models.

    Methodology:

        Data preprocessing and visualization

        Feature scaling

        Building an LSTM model using TensorFlow/Keras

        Model training and evaluation

    Outcome: A trained LSTM model capable of predicting future WFC stock price trends with reasonable accuracy.

# 🧠 Technologies Used

    Python 🐍

    Jupyter Notebook 📓

    TensorFlow & Keras 🤖

    Numpy & Pandas 📊

    Scikit-learn 🧮

    Matplotlib & Seaborn 📉

    Yahoo Finance API (via yfinance) 💹

# 📊 Dataset

    Source: Yahoo Finance

    Ticker: WFC (Wells Fargo & Company)

    Fields Used: Open, High, Low, Close, Volume, and Date

    Timeframe: Varies depending on current date and model scope

# 🔧 Model Architecture

    Input Layer: Sequence of past stock prices

    LSTM Layer: Captures temporal dependencies

    Dense Layer: Outputs predicted stock price

    Loss Function: Mean Squared Error (MSE)

    Optimizer: Adam

# 📈 Results

    Visual comparison between actual and predicted stock prices

    Loss curve showing convergence of the LSTM model
