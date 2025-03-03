# Stock Price Forecasting using LSTM

## Project Overview

This project uses **Long Short-Term Memory (LSTM)**, a type of recurrent neural network (RNN), to predict future stock prices based on historical data of Apple Inc. (AAPL). The goal is to forecast stock prices for the next 30 days using past price and volume data.

## Key Features

- **Data Preprocessing**: The dataset includes Open, Close, High, Low, and Volume values, which are preprocessed using **MinMaxScaler** to normalize the values.
- **LSTM Model**: An LSTM neural network is used to model the time-series data and make predictions for future stock prices.
- **Stock Price Prediction**: The trained model predicts stock prices for the next 30 days, which are then plotted alongside actual values for comparison.
- **Model Evaluation**: The model’s performance is evaluated using **RMSE** (Root Mean Squared Error) and **R² Score**.

## Tools Used

- **Python**
- **PyTorch**: For building and training the LSTM model.
- **Pandas**: For data manipulation.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **Scikit-learn**: For data preprocessing and evaluation metrics.

## Installation

### Requirements

1. **Python 3.x** (recommended Python 3.7 or later)
2. Required libraries:
pip install numpy pandas matplotlib scikit-learn torch tqdm

### Running the Project

1. Clone the repository or download the project files.
2. Place the dataset (Apple stock price data in CSV format) in the appropriate folder.
3. Run the Python script to train the LSTM model and visualize the forecast.

```bash
python stock_price_forecasting.py
