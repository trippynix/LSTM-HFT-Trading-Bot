# LSTM-HFT-Trading-Bot
This is a prototype high frequency trading bot created for trading US30 or DJI in 1 minute timeframe.
The trained model which gave me the best result was able to perform okayish during 8pm to 8:30pm IST but it was 
not profitable.
As this is a prototype I do not recommend anyone to try and use this bot.
Using LSTM the predicted prices were lagging in avg 4-5 points. But sometimes it predicted reversals and caught good moves.
If we introduce some extra parameters, rules and implement a strategy with this prediction we can make a profitable bot.
The bot predicts OHLC for next candle based on prev 30 candles.
"US30 1m.keras" is the model that gave me best performance.
"US30 1m LSTM.ipynb" is the code for training the model.
"LSTM US30 1m deployment-Copy1.ipynb" is the deployment on live data code.
