# Stock-price-predict
#Features
Predict stock prices using LSTM model. Visualize moving averages (MA50, MA100, MA200). Compare actual stock prices with predicted prices. User-friendly web interface using Streamlit. Data Source: Yahoo Finance Stock: Google (GOOG) (or any stock symbol entered by the user) 
#LSTM Model Architecture
4 LSTM layers with 50, 60, 80, and 120 units, each followed by a Dropout layer to prevent overfitting. The model is trained to predict stock prices based on the last 100 days of stock data.
#Results
The model predicts future stock prices with reasonable accuracy, and the web app provides a comparison between predicted prices and actual historical prices. Screenshots Stock Data Visualization: Visualizes the stock prices with MA50, MA100, and MA200.

Price Prediction: Compares predicted prices vs. actual prices.

#Model Training
The model was trained for 50 epochs using the Adam optimizer and Mean Squared Error (MSE) as the loss function. It predicts the stock price for the next day based on the last 100 days of data.

