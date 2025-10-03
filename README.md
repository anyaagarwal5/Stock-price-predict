Stock Price Predictor

Predict stock prices using an LSTM model and visualize results through a user-friendly Streamlit web interface.

Features

Predict future stock prices using LSTM.

Visualize moving averages: MA50, MA100, MA200.

Compare actual stock prices with predicted prices.

User-friendly web interface with Streamlit.

Data source: Yahoo Finance (user can input any stock symbol, e.g., Google (GOOG)).

LSTM Model Architecture

4 LSTM layers with 50, 60, 80, and 120 units, each followed by a Dropout layer to prevent overfitting.

Trained to predict stock prices based on the last 100 days of stock data.

Model Training

Trained for 50 epochs using the Adam optimizer.

Loss function: Mean Squared Error (MSE).

Predicts the stock price for the next day based on the last 100 days of historical data.

Results

The model predicts future stock prices with reasonable accuracy.

The web app provides comparisons between predicted prices and actual historical prices.

Screenshots

Stock Data Visualization – Shows stock prices with MA50, MA100, and MA200.

Price Prediction – Compares predicted prices vs actual prices.

