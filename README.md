## Stock Market Anomaly Detection

## Overview
This project focuses on detecting abnormal movements in stock market prices such as
sudden spikes, crashes, and unusual volatility using statistical and machine learning
based anomaly detection techniques.

## Dataset
Historical stock price data is collected using the Yahoo Finance API.

## Feature Engineering
- Daily Returns
- Rolling Mean (20-day)
- Rolling Volatility (20-day)
- Trading Volume

## Anomaly Detection Techniques
- Z-Score (Statistical Baseline)
- Isolation Forest
- Local Outlier Factor (LOF)

## Results
Isolation Forest provided the most robust anomaly detection by identifying significant
market movements while avoiding excessive false positives compared to Z-score and LOF.

## Technologies Used
- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- yfinance

## Future Work
- Real-time anomaly detection
- Autoencoder-based deep learning models
- Multi-stock analysis
