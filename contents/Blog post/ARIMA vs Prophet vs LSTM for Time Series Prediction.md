---
already_read: false
link: https://neptune.ai/blog/arima-vs-prophet-vs-lstm
read_priority: 1
relevance: 0
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-01-25'
---

https://neptune.ai/blog/arima-vs-prophet-vs-lstm
## Summary

The content compares three time series prediction models: ARIMA, Prophet, and LSTM.

**ARIMA (AutoRegressive Integrated Moving Average)** is a classic time series model that uses past values and errors to predict future values. It requires the time series to be stationary, which can be achieved through differencing. The model is defined by three parameters: p (number of past values), d (number of differences), and q (number of past errors).

**Prophet** is a model developed by Facebook for business time series prediction. It is an additive model with four components: trend, seasonality, holidays, and an error term. Prophet is designed to handle business time series and requires less hyperparameter tuning.

**LSTM (Long Short-Term Memory)** is a type of recurrent neural network that can learn from sequential data. LSTMs use gates to learn important parts of the sequence and forget less important ones. They are powerful but require careful hyperparameter tuning and can be prone to overfitting.

The content also discusses an experimental evaluation of these models using stock exchange data. The models were compared using metrics like root mean square error (RMSE) and mean absolute error (MAE). ARIMA achieved the best performance, while LSTM performed the worst due to overfitting. The content concludes with a summary of each model's advantages and limitations and provides resources for further learning.
## Links

- [PMD ARIMA Documentation](http://alkaline-ml.com/pmdarima/) : Documentation for the PMD ARIMA Python package, used for time series forecasting with ARIMA models.
- [Facebook Prophet Documentation](https://facebook.github.io/prophet/) : Official documentation and tutorial for Facebook's Prophet, a forecasting tool designed for business time series data.
- [Keras LSTM Documentation](https://keras.io/api/layers/recurrent_layers/lstm/) : Documentation and examples for implementing LSTM recurrent neural networks in Keras.
- [Neptune Experiment Tracking](https://docs.neptune.ai/) : Documentation for Neptune, an experiment tracking tool that helps in logging, storing, and comparing model-building metadata.

## Topics

![](topics/Model/ARIMA)

![](topics/Model/Prophet)

![](topics/Model/LSTM)

![](topics/Tool/Neptune)

![](topics/Concept/Time%20Series%20Prediction)

![](topics/Concept/Feature%20Engineering)