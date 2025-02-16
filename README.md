# Bitcoin Price Predictor

## 📌 Overview

This project aims to build a machine learning model to predict Bitcoin prices using historical price data and Wikipedia edits data. The goal is to combine financial data with sentiment analysis from Wikipedia to create a comprehensive dataset for analysis and prediction. The project provides real-time sentiment analysis and predictive modeling using Jupyter notebooks. It consists of two primary notebooks:

1. **`sentiments_live.ipynb`** - Performs live sentiment analysis on input data, leveraging NLP techniques.
2. **`prediction_live.ipynb`** - Generates predictions using machine learning models, analyzing trends and insights.

## 📊 Data Sources

- **Yahoo Finance**: Bitcoin price data relative to USD.
- **Wikipedia Edits**: Sentiment analysis data from Wikipedia edits related to Bitcoin.

## 🛠 Features

- Historical Bitcoin prices (Open, High, Low, Close, Volume).
- Wikipedia Edit Data (Edit Count, Sentiment, Negative Sentiment).
- **Target Variable**: Whether Bitcoin’s closing price will increase the next day (Binary Classification).
- Real-time sentiment analysis using Natural Language Processing (NLP).
- Predictive modeling for trend forecasting.
- Live data streaming and visualization.
- Interactive Jupyter notebooks for easy exploration.

## 🤖 Machine Learning Models

The project employs two machine learning models for Bitcoin price prediction:

1. **XGBoost** - Gradient boosting framework for high-performance predictions.
2. **RandomForestClassifier** - Ensemble learning model that improves prediction accuracy.




