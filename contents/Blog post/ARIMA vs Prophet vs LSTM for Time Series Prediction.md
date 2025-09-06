---
already_read: false
link: https://neptune.ai/blog/arima-vs-prophet-vs-lstm
read_priority: 1
relevance: 0
source: null
tags:
- Time_Series
- Data_Analysis
type: Content
upload_date: '2024-01-25'
---

https://neptune.ai/blog/arima-vs-prophet-vs-lstm
## Summary

The blog post compares three time series prediction models: ARIMA, Prophet, and LSTM. ARIMA (AutoRegressive Integrated Moving Average) is a classic model that uses past values and errors for prediction, requiring the time series to be stationary. Prophet, developed by Facebook, is designed for business time series and includes trend, seasonality, and holiday components. LSTM (Long Short-Term Memory) is a type of recurrent neural network that learns from sequential data, using gates to manage information flow.

The evaluation uses stock exchange data to predict the Volume Weighted Average Price (VWAP). ARIMA is implemented using the `pmdarima` library with auto-tuning for parameters. Prophet is used with added exogenous features, and LSTM is implemented using Keras with a custom architecture. The models are compared using Neptune.ai for experiment tracking, with ARIMA achieving the best performance, followed by Prophet, and LSTM performing the worst due to overfitting.

Key takeaways:
- ARIMA is powerful but requires careful hyperparameter tuning.
- Prophet is effective for business time series but may struggle with non-business data.
- LSTM is versatile but complex, requiring large datasets and careful tuning to avoid overfitting.
- Neptune.ai is used for tracking and comparing model performance.
## Links

- [PMD ARIMA Documentation](http://alkaline-ml.com/pmdarima/) : Documentation for the PMD ARIMA Python package, used for time series forecasting with ARIMA models.
- [Facebook Prophet Documentation](https://facebook.github.io/prophet/) : Official documentation and tutorial for Facebook's Prophet, a tool for forecasting time series data.
- [Keras LSTM Documentation](https://keras.io/api/layers/recurrent_layers/lstm/) : Documentation and examples for implementing LSTM recurrent neural networks in Keras.
- [Neptune.ai Documentation](https://docs.neptune.ai/) : Documentation for Neptune.ai, an experiment tracking tool for machine learning models.
- [Original Prophet Research Paper](https://peerj.com/preprints/3190.pdf) : The original research paper introducing Facebook's Prophet for time series forecasting.

## Topics

![](topics/Concept/Time%20Series%20Prediction)

![](topics/Model/ARIMA)

![](topics/Model/Prophet)

![](topics/Model/LSTM)

![](topics/Tool/Neptune)