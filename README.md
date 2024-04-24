
# Weather Data Compression for Ensemble Forecasting

This project attempts to reduce the dimensionality of time series data, in this case weather data.

## Method

This project implements a Variational Autoencoder with an added loss value - how well a forecast model can predict the next value using the latent space, encoded by the RMSE between the decoded forecast and the forecast from the original data.