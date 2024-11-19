# Stock Price Prediction Using Deep Learning (LSTM)

This repository contains the implementation of a stock price prediction model using **Long Short-Term Memory (LSTM)** networks. The project explores various preprocessing techniques, including **Normalization**, **Simple Moving Averages (SMA)**, and **Discrete Wavelet Transform (DWT)**, to enhance model accuracy and performance.

## Project Overview

Stock market prediction is a challenging task due to the complex and noisy nature of financial data. This project aims to develop a robust model that leverages deep learning techniques to forecast stock prices with high accuracy. 

Key highlights:
- Preprocessing raw data with advanced techniques to improve prediction reliability.
- Training an LSTM model to capture sequential dependencies in stock price data.
- Evaluation of model performance using metrics such as MSE, RMSE, and R-squared.

## Features

- **Data Preprocessing**:
  - **Normalization**: Scales data between 0 and 1 for efficient learning.
  - **SMA**: Smoothens data to identify trends.
  - **DWT**: Removes high-frequency noise while retaining meaningful patterns.
  
- **LSTM Model Architecture**:
  - Multiple LSTM layers for sequential learning.
  - Dropout layers to prevent overfitting.
  - Dense layers for final predictions.

- **Visualization**:
  - Graphs showing training vs validation loss, predicted vs actual prices, and next-day predictions.

## Dataset

The dataset includes historical stock prices for IBM (2003–2024), sourced from Yahoo Finance. The key attributes are:
- Open, High, Low, Close prices
- Trading Volume

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
