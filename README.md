# Deep Learning for Prediction of stock price movement using momentum 

## Abstract

Applying machine learning techniques to historical stock market data has recently gained traction, mostly focusing on the American stock market. We add to the literature by applying similar methods to the Canadian stock market, focusing on time series analysis for basic momentum as a starting point. We apply long-short term memory networks (LSTMs), a type of recurrent neural network and do a comparative analysis of the results of a LSTM to a logistic regression (LOG) approach as well as a basic momentum strategy for portfolio formation. Our results show that the LSTM financially outperforms both the LOG and basic momentum strategy, however the area under the curve of the receiver operating characteristic curves show the results do not outperform a random walk selection. We conclude that there might not be enough data in monthly returns for the LSTM in its current configuration.

## Repository Structure

- exploratory_notebooks: initial notebooks used to prepare final analysis code
- final_notebooks: final notebooks used to run the different strategies and models
- paper: the final written paper on the work

## Data

The data for this research was obtained through CHASS:http://clouddc.chass.utoronto.ca/ds/cfmrc/. 
The data is Canadian stock price and return data going back to 1985.
