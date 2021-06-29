# LSTM Stock Predictor
### Background
Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, it was used deep learning recurrent neural networks to model bitcoin closing prices. One model used the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

It was needed to:

1. Prepare the data for training and testing
2. Build and train custom LSTM RNNs]
3. Evaluate the performance of each model]


Using the testing data, it was evaluated each model and compared the performance to answer the question below:

> Which model has a lower loss?
> The model with the lower loss is the closing prices predictor

> Which model tracks the actual values better over time?
> The model with better results over time is the closing prices predictor

> Which window size works best for the model?
> The window size that works better is 10

> Also, it was interesting to note that 