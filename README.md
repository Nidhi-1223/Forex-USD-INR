# Foreign Exchange Forecast
Forex forecast refers to the prediction or estimation of future movements in currency exchange rates. It involves analyzing various factors, such as economic indicators, geopolitical events, market trends, and technical analysis, to anticipate the direction and potential magnitude of currency price fluctuations.

The notebook presented focuses on forecasting foreign exchange rates specifically between the Indian Rupee (INR) and the US Dollar (USD). To achieve this, historical financial rate data spanning from 2010 to 2023 is gathered. This data is obtained by scraping information from the [provided link](https://in.investing.com/currencies/streaming-forex-rates-majors), which is a reliable source for streaming forex rates of major currencies.

The forecasting process employs a Stacked LSTM (Long Short-Term Memory) model. LSTM is a type of recurrent neural network (RNN) that is effective in handling sequential data, making it suitable for time series forecasting tasks. By utilizing a stacked architecture, multiple LSTM layers are stacked on top of each other, allowing the model to capture more complex patterns and dependencies in the data.

The Stacked LSTM model is trained on the collected historical financial rate data, where it learns the patterns and relationships between various factors that influence the INR-USD exchange rates. By analyzing the historical data, the model can identify trends and patterns, enabling it to make predictions about future exchange rates.







