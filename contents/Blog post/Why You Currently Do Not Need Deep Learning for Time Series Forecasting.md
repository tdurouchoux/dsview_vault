---
already_read: false
link: https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
read_priority: 1
relevance: 0
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-07-03'
---

https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
## Summary

The article discusses why Deep Learning is currently not necessary for time series forecasting and emphasizes the effectiveness of other forecasting methods, particularly based on insights from the Makridakis M5 competitions and the 2023 Kaggle AI report.

Key points include:

- **Model Performance**: Machine Learning (ML) models, especially Gradient Boosting Machines (like LightGBM, XGBoost, and CatBoost), outperform statistical models and deep learning models in time series forecasting tasks. ML models are effective, require minimal feature engineering, and allow fast iterations.

- **Statistical Methods**: While ML models dominate, basic statistical methods remain valuable as baseline models, with many ML approaches failing to outperform simple heuristics.

- **Ensemble Methods**: Combining different models through ensembling can improve forecast accuracy, although it adds complexity.

- **Feature Engineering**: Good feature extraction and engineering is more critical than the choice of model. Real-world data typically requires extensive cleaning and thoughtful feature creation to enhance model performance.

- **Exogenous Variables**: Incorporating external explanatory variables can significantly boost forecasting accuracy, highlighting the importance of understanding the context of the time series.

- **Iteration and Validation**: Rapid testing of different models and features is important, along with using robust cross-validation strategies to avoid overfitting and identify the best models.

- **Unique Solutions**: Each forecasting problem requires a tailored approach, with no one-size-fits-all solution. Current deep learning architectures struggle to adapt effectively to the specifics of time series tasks.

The article concludes that while deep learning remains a relevant topic, it is not yet effective for practical applications in time series forecasting. The emphasis is placed on learning from competition outcomes and focusing on the importance of ML, baseline methods, and feature engineering for superior forecasting performance.
## Links

- [N-HiTS: Making Deep Learning for Time Series Forecasting More Efficient](https://towardsdatascience.com/n-hits-making-deep-learning-for-time-series-forecasting-more-efficient-d00956fc3e93) : An article discussing the N-HiTS model and its efficiency in time series forecasting.
- [Why You Should Always Start With a Baseline Model](https://pub.towardsai.net/why-you-should-always-start-with-a-baseline-model-95d78c70941c) : An article emphasizing the importance of baseline models in achieving reasonable forecasting results.
- [Kaggle AI Report 2023](https://kaggle.com/competitions/2023-kaggle-ai-report) : The latest Kaggle competition report featuring key learnings and trends in AI.
- [N-BEATS: The First Interpretable Deep Learning Model That Worked for Time Series Forecasting](https://towardsdatascience.com/n-beats-the-first-interpretable-deep-learning-model-that-worked-for-time-series-forecasting-06920daadac2) : An article explaining the N-BEATS model for time series forecasting and its interpretability.
- [Kaggle M5 Competition Overview](https://www.sciencedirect.com/science/article/pii/S0169207021001874) : A comprehensive overview of the M5 competition and its significance in forecasting challenges.

## Topics

![](topics/Concept/Hybrid%20Models)

![](topics/Library/LightGBM)

![](topics/Library/XGBoost)

![](topics/Library/CatBoost)

![](topics/Concept/Ensemble%20Methods)

![](topics/Concept/Feature%20Engineering)

![](topics/Concept/Probabilistic%20Forecasting)

![](topics/Concept/Cross%20Validation)

![](topics/Concept/Explanatory%20Variables)