# 📈 Forecasting Wells Fargo Stock Price Using Neural Networks & Machine Learning

This project applies classical machine learning algorithms and deep learning (LSTM) to predict the directional movement of **Wells Fargo & Co. (WFC)** stock price. The objective is to forecast whether the stock will close higher the next day using historical price data and engineered features.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Data Collection](#data-collection)
- [EDA & Feature Engineering](#eda--feature-engineering)
- [Models Implemented](#models-implemented)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Results](#key-results)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Future Work](#future-work)
- [License](#license)

---

## 🧠 Overview

The goal is to build a predictive model that can classify whether Wells Fargo's stock price will **go up (1)** or **go down/stay the same (0)** the following day based on engineered features and time series trends. The project compares traditional ML classifiers with an LSTM model to evaluate performance on sequential financial data.

---

## 📥 Data Collection

- Data Source: [Yahoo Finance](https://finance.yahoo.com/)
- Collected using: `yfinance` Python package
- Data Range: 5 years of historical daily data
- Features extracted: Open, High, Low, Close, Volume, and Date

---

## 📊 EDA & Feature Engineering

- Visualizations of stock prices and volatility trends using Matplotlib and Seaborn
- Key engineered features:
  - `open-close`: Daily price change
  - `low-high`: Daily volatility
  - `quarter`: Binary indicator for end-of-quarter trading
  - `target`: Binary label for stock price increase the next day

---

## 🤖 Models Implemented

### Classical Machine Learning
- Logistic Regression
- Support Vector Machine (SVC with Polynomial Kernel)
- XGBoost Classifier

### Deep Learning
- LSTM (Long Short-Term Memory) Neural Network  
  - Built using Keras and TensorFlow  
  - Input structured with sliding time windows  
  - Trained using binary cross-entropy loss

---

## 📈 Evaluation Metrics

All models were evaluated using:
- ROC-AUC Score
- Classification Accuracy
- Confusion Matrix (for insights into false positives/negatives)

---

## ✅ Key Results

- **XGBoost** achieved the highest performance among classical models.
- **LSTM outperformed all others** by capturing temporal dependencies in price sequences.
- Engineered features like `open-close` and `quarter` were influential predictors.

---

## 🛠️ Technologies Used

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Keras, TensorFlow, yfinance
