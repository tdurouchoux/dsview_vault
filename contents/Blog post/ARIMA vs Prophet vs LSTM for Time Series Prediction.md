---
already_read: false
link: https://neptune.ai/blog/arima-vs-prophet-vs-lstm?utm_source=substack&utm_medium=email
read_priority: 1
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-01-25'
---

https://neptune.ai/blog/arima-vs-prophet-vs-lstm?utm_source=substack&utm_medium=email
## Summary

The content compares three popular time series prediction methods: ARIMA, Prophet, and LSTM. 

1. **ARIMA (AutoRegressive Integrated Moving Average)**:
   - Utilizes past values and past errors to predict future values.
   - Requires the time series to be stationary, often achieved through differencing.
   - Defined by three parameters: p (number of past values), d (number of differences for stationarity), and q (number of past errors).
   - Achieved the best performance in the evaluation.

2. **Prophet**:
   - Developed by Facebook for business time series forecasting.
   - An additive model with components for trend, seasonality, and holidays.
   - Requires less hyperparameter tuning and is effective for business-related time series but may struggle with non-business datasets.

3. **LSTM (Long Short-Term Memory)**:
   - A type of recurrent neural network that learns from sequences of data.
   - Uses gates to manage information retention and forgetting.
   - Requires careful hyperparameter tuning and is prone to overfitting, especially with smaller datasets, which led to poorer performance in this evaluation.

**Experimental Evaluation**:
- The models were tested on stock exchange data for Bajaj Finserv Ltd, predicting the Volume Weighted Average Price (VWAP).
- Feature engineering was applied to enhance model input.
- ARIMA outperformed both Prophet and LSTM in terms of accuracy metrics (RMSE and MAE).

**Conclusions**:
- Each model has its strengths and weaknesses:
  - ARIMA is powerful but requires careful tuning.
  - Prophet is user-friendly for business applications but may not generalize well.
  - LSTM is versatile but complex and sensitive to dataset size.
- Future directions include exploring more resources and tools for time series analysis.
## Links

1. [PMD ARIMA](http://alkaline-ml.com/pmdarima/) - Documentation for the PMD ARIMA Python package, which is used for implementing ARIMA models.
2. [Prophet](https://facebook.github.io/prophet/) - Documentation and tutorial for Facebook's Prophet, a tool designed for forecasting time series data.
3. [Keras LSTM](https://keras.io/api/layers/recurrent_layers/lstm/) - Documentation for the Keras implementation of Long Short-Term Memory (LSTM) networks, which are used for sequence prediction.
4. [AIC value](https://en.wikipedia.org/wiki/Akaike_information_criterion) - Wikipedia page explaining the Akaike Information Criterion, a measure used for model selection.
5. [Time Series Prediction with LSTM](https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/) - A tutorial on using LSTM for time series prediction, providing practical insights and examples.
## Topics

- [[topics/Model/ARIMA]]
- [[topics/Model/Prophet]]
- [[topics/Model/LSTM]]
- [[topics/Library/pmdarima]]
- [[topics/Library/Prophet]]