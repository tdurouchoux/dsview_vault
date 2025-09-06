---
already_read: false
link: https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
read_priority: 1
relevance: 0
source: null
tags:
- Time_Series
- Supervised_Learning
type: Content
upload_date: '2024-07-03'
---

https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
## Summary

The article discusses why deep learning may not be the best choice for time series forecasting currently, based on findings from the Makridakis M5 competitions and the 2023 Kaggle AI report, as well as the author's personal experience.

Key points include:

1. **Superior Performance of ML Models**: Machine learning (ML) models, particularly Gradient Boosting Machines (GBMs) like LightGBM, XGBoost, and CatBoost, have shown superior performance in recent competitions and are preferred for their speed, ease of use, and effectiveness.

2. **Value of Statistical Methods**: Despite the rise of ML models, statistical methods still hold value as baseline models and can be useful for decision-making and understanding data.

3. **Ensembles Improve Performance**: Combining different models through ensembling can improve forecast accuracy, but it also adds complexity and may reduce explainability.

4. **Gap Between Scientific Literature and Practice**: Deep learning models, which are often the focus of scientific literature, are not widely used in practice due to their complexity and cost.

5. **Importance of Feature Engineering**: Good feature engineering is crucial and often more important than the choice of model. It involves cleaning data, identifying good features, and using domain knowledge.

6. **Exogenous Variables**: Incorporating external data can significantly boost model performance.

7. **Iteration and Cross-Validation**: Fast iteration and effective cross-validation strategies are essential for identifying the best features and models.

8. **Unique Approaches for Each Problem**: Every problem requires a unique approach, and deep learning models are not yet practical for real-world applications due to their one-size-fits-all approach.

The article concludes that while deep learning is not currently useful for real-world time series forecasting, there is potential for future improvements, and staying updated on developments is important. The most important factors for successful time series forecasting include the use of ML models, statistical methods, ensembling, feature engineering, exogenous variables, fast iteration, effective cross-validation, and unique approaches for each problem.
## Links

- [N-HiTS — Making Deep Learning for Time Series Forecasting More Efficient](https://towardsdatascience.com/n-hits-making-deep-learning-for-time-series-forecasting-more-efficient-d00956fc3e93) : A deep dive into how N-HiTS works and how you can use it
- [Why You Should Always Start With a Baseline Model](https://pub.towardsai.net/why-you-should-always-start-with-a-baseline-model-95d78c70941c) : A baseline model takes 10% of the time to develop but gets us 90% of the way to achieve reasonable results.
- [N-BEATS — The First Interpretable Deep Learning Model That Worked for Time Series Forecasting](https://towardsdatascience.com/n-beats-the-first-interpretable-deep-learning-model-that-worked-for-time-series-forecasting-06920daadac2) : An easy-to-understand deep dive into how N-BEATS works and how you can use it.

## Topics

![](topics/Model/Gradient%20Boosting%20Machines%20GBMs)

![](topics/Model/LightGBM)

![](topics/Model/CatBoost)

![](topics/Concept/Ensembling)

![](topics/Model/XGBoost)

![](topics/Concept/Feature%20Engineering)