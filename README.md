# Encephalon v1.0

A **barebone** market price prediction neural network.


## About

Encephalon is a neural network that gathers past market price data and uses LSTM to predict the next day's price.
The default asset is Bitcoin (BTC/USD).

*Disclaimer:
This project is only purely for research, programming and education purposes. It is not recommended that you take investing/finance decisions or advice based upon the output of this project.
I **do not take responsibility** for any investment/financial decisions you may/may not take. Seek professional advice before taking action.*

## Prerequisites

This project uses the following:

 - Numpy
 - Matplotlib (Matplotlib.pyplot)
 - Pandas
 - Pandas_datareader
 - datetime
 - Tensorflow
 - Scikit (sklearn)
 - Yahoo Finance (yfinance)

## How to use?

You can change the amount of past data it gathers under the variable `prediction_days`. The default is 60 days. Keep in mind, the bot is only designed to predict the price of the next day, so I suggest keeping the prediction days somewhere in the range of 60-10 days.
You can also optimize the neural network by messing around with the scalers under `# Data Preparation`.

## Version

Currently on version 1.0.
Many hyper-optimizations are needed, coming soon in future versions.
