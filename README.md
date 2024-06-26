# Google Stock Price Prediction

<h2> Overview</h2>
This project focuses on predicting stock prices using Long Short-Term Memory (LSTM) neural networks, a type of recurrent neural network (RNN) well-suited for sequential data such as time series. The LSTM model is trained on historical stock price data of Google (ticker symbol 'GOOG') spanning from January 2010 to December 2022. The trained model is then used to forecast stock prices for the year 2023.
<h2> Data Preparation </h2>

<b>Data Acquisition:</b> Historical stock price data is fetched using the Yahoo Finance API (yfinance). This data includes Open, High, Low, Close prices, and Volume.

<b>Data Preprocessing:</b> Data cleaning, normalization using MinMaxScaler, and structuring into sequences suitable for LSTM training.

<h2>Model Training</h2>h2>
<b>Model Architecture:</b> Sequential LSTM model with multiple layers and dropout regularization to prevent overfitting.

<b>Training:</b> The model is trained on historical data from January 2010 to December 2022.

<h2>Evaluation</h2>
<b>Metrics:</b> Performance evaluation metrics include Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

<b>Visualization:</b> Visualizations are generated to compare predicted and actual stock prices, providing insights into the model's accuracy.

<h2>Results</h2>

<b>Training Data (2010-2022):</b>

MAE: 9.49%<br>
MSE: 15083.69<br>
RMSE: 122.82<br>
R2 Score: 0.97<br>

<h2> Prediction for 2023</h2>

MAE: 12.13%<br>
MSE: 45897.90<br>
RMSE: 214.24<br>
R2 Score: 0.89<br>
