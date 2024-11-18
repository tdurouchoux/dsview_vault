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

The article compares three popular time series prediction methods: ARIMA, Prophet, and LSTM. 

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
   - More powerful for complex patterns but requires careful tuning and can overfit on smaller datasets, as observed in the evaluation.

**Experimental Evaluation**:
- The models were tested on stock exchange data for Bajaj Finserv Ltd from 2008 to 2021, predicting the Volume Weighted Average Price (VWAP).
- Feature engineering was applied to enhance model performance.
- ARIMA outperformed both Prophet and LSTM in terms of accuracy metrics (RMSE and MAE).

**Conclusions**:
- ARIMA is effective but requires careful tuning.
- Prophet is user-friendly for business applications but may not generalize well.
- LSTM is powerful for large datasets but complex and prone to overfitting on smaller datasets.

The article emphasizes the importance of understanding the strengths and limitations of each model for effective time series forecasting.
## Links

1. [Prophet Documentation](https://facebook.github.io/prophet/) - Official documentation for Facebook's Prophet, a tool designed for forecasting time series data.
2. [Keras LSTM Documentation](https://keras.io/api/layers/recurrent_layers/lstm/) - Documentation for LSTM layers in Keras, detailing how to implement LSTM networks for sequential data.
3. [PMD ARIMA Documentation](http://alkaline-ml.com/pmdarima/modules/generated/pmdarima.arima.auto_arima.html#pmdarima.arima.auto_arima) - Documentation for the pmdarima package, which provides tools for ARIMA modeling in Python.
4. [Time Series Prediction with LSTM](https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/) - A tutorial on using LSTM for time series prediction, providing practical examples and code.
5. [Remove Trends and Seasonality in Time Series](https://machinelearningmastery.com/remove-trends-seasonality-difference-transform-python/) - A guide on how to preprocess time series data by removing trends and seasonality, which is crucial for effective modeling.
## Topics

![](topics/Model/ARIMA)

![](topics/Model/Prophet)

![](topics/Model/LSTM)

![](topics/Library/pmdarima)

![](topics/Library/Prophet)