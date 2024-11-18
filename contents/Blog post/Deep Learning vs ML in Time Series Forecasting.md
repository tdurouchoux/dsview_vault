---
already_read: false
link: https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
read_priority: 1
source: null
tags:
- Time_Series
- Deep_Learning
type: Content
upload_date: '2024-07-03'
---

https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
## Summary

The article argues against the necessity of deep learning for time series forecasting, emphasizing that traditional machine learning (ML) methods and statistical models often yield better results. Key insights are drawn from the Makridakis M5 competitions and the 2023 Kaggle AI report, which highlight the following points:

1. **ML Dominance**: ML models, particularly Gradient Boosting Machines (GBMs) like LightGBM, XGBoost, and CatBoost, have outperformed deep learning models in recent competitions due to their efficiency, ease of use, and superior performance on various datasets.

2. **Statistical Models**: Despite the rise of ML, simple statistical models remain valuable as baselines, often outperforming complex ML models in many cases.

3. **Ensemble Methods**: Combining different models can enhance forecast accuracy, especially when individual models make uncorrelated errors. However, simpler ensembles are preferred for ease of maintenance.

4. **Feature Engineering**: The article stresses that effective feature engineering is more critical than the choice of model. Time spent on cleaning data and creating informative features significantly impacts model performance.

5. **Exogenous Variables**: Incorporating external data can greatly improve forecasting accuracy, as these variables often influence the time series being predicted.

6. **Rapid Iteration**: Fast experimentation with various features and models is essential for finding the best solution, with LightGBM being favored for its quick training times.

7. **Cross-Validation**: A robust cross-validation strategy is crucial for objectively assessing model performance and avoiding overfitting.

8. **Unique Approaches**: Each forecasting problem requires a tailored approach, as there is no one-size-fits-all solution.

The conclusion emphasizes that while deep learning has potential, it has not yet proven effective in practical applications for time series forecasting, and current best practices favor ML and statistical methods.
## Links

1. [Kaggle AI Report 2023](https://kaggle.com/competitions/2023-kaggle-ai-report) - A collection of essays and key learnings from the Kaggle community regarding recent high-performing solutions in AI competitions.
2. [N-BEATS: The First Interpretable Deep Learning Model That Worked for Time Series Forecasting](https://towardsdatascience.com/n-beats-the-first-interpretable-deep-learning-model-that-worked-for-time-series-forecasting-06920daadac2) - An overview of the N-BEATS model, which aims to provide interpretability in time series forecasting.
3. [N-HiTS: Making Deep Learning for Time Series Forecasting More Efficient](https://towardsdatascience.com/n-hits-making-deep-learning-for-time-series-forecasting-more-efficient-d00956fc3e93) - A deep dive into the N-HiTS model, focusing on its efficiency in time series forecasting tasks.
4. [Why You Should Always Start With a Baseline Model](https://pub.towardsai.net/why-you-should-always-start-with-a-baseline-model-95d78c70941c) - An article discussing the importance of baseline models in achieving reasonable results in forecasting.
5. [Statistical Methods in Time Series Forecasting](https://www.sciencedirect.com/science/article/pii/S0169207021001722) - A scientific article exploring the role of statistical methods in time series forecasting and their effectiveness compared to machine learning approaches.
## Topics

![](topics/Concept/Feature%20Engineering)

![](topics/Product/LightGBM)

![](topics/Product/XGBoost)

![](topics/Product/CatBoost)

![](topics/Concept/Ensemble%20Learning)