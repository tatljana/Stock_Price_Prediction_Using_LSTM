# Stock_Price_Prediction_Using_LSTM
Stock, forex or cryptocurrency price 50-day forecast using LSTM

<b>Please view the file in <a href='https://nbviewer.org/github/tatljana/Stock_Price_Prediction_Using_LSTM/blob/main/Stock_Price_Prediction_LSTM.ipynb'>nbviewer</a> for the nice rendering of interactive plotly graphs!</b>

<p>This was a project for one of my university subjects that focuses on math and finance from a programming perspective, where all the work was done in Python using Google Colab. LSTM was a weird choice for the first project in ML, but every other ML model that came after this one was easy peasy to understand and it really got me into machine learning.</p>

<p>Program imports 6 years' worth of data from Yahoo Finance for the ticker of choice. Sequences of 50 closing prices are used to train and test the model. That model is then used to predict prices for the next 50 days. If a certain ticker has less than 6 years of data, the program imports all available data.

<p>Disclaimer: Stock price can't truly be predicted, but there are patterns and indicators that can help traders to form an opinion on how the price will be moving throughout the hour or day. Predicting 50 days far into the future is pointless from a pragmatic perspective, thus it's clear that this model is not to be used for actual trading.</p>

<p>Note that the model can be used for stocks, stock market indexes (e.g. S&P 500), forex, and cryptocurrencies. But, since cryptocurrencies are pretty young, some of them won't have enough data for a solid model training, which will result in a less accurate model (e.g. Polkadot was launched in 2020 and would only give us 2 years of data). The same goes for companies with recent initial public offerings.</p>
