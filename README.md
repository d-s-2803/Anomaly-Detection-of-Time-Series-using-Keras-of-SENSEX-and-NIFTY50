# Anomaly-Detection-of-Time-Series-using-Keras-of-SENSEX-and-NIFTY50

Anomaly detection problem for time
series refers to finding outlier data points relative to
some standard or usual signal. A price action that
contradicts the expected movement of the stock market
is called an anomaly. Few anomalies appear only once
and disappear, but there are some that appear
consistently throughout historical chart analysis.
Traders and investors are benefitted from these unusual
market behaviors to find opportunities throughout the
stock market. While there are plenty of anomaly types,
we have focused only on the most important ones such as
unexpected spikes i.e., sudden rise in the prices, drops
i.e., sudden fall in the prices, trend changes and level
shifts. Using Long Short-Term Memory (LSTM) we have
predicted the points where there might be a possible
anomaly in the time series. Using the time series of
SENSEX and NIFTY50 over the last 25 years we have
predicted the possible anomaly in the time series. We
have first imported the libraries, loaded and inspected
the data of both SENSEX and NIFTY50. We have then
processed the data and then created and split the data
into test and train dataset. Then we have built an LSTM
Autoencoder. An LSTM Autoencoder is an
implementation of an autoencoder for sequence data
using an Encoder-Decoder LSTM architecture. Once fit,
the encoder part of the model can be used to encode or
compress sequence data that in turn may be used in data
visualizations or as a feature vector input to a supervised
learning model. We have then evaluated the model and
then detected the possible anomalies in the entire
dataset.
