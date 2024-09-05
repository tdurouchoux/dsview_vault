---
already_read: false
link: https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
read_priority: 1
source: null
tags:
- Time_Series
- Feature_Engineering
type: Content
upload_date: '2024-07-03'
---

https://readmedium.com/en/why-you-currently-do-not-need-deep-learning-for-time-series-forecasting-0de57f2bc0ed
## Summary

Deep Learning is currently not the best choice for time series forecasting, with Machine Learning (ML) models, particularly Gradient Boosting Machines (GBMs) like LightGBM, XGBoost, and CatBoost, outperforming them in both competitions and real-world applications. These ML models are favored for their superior performance, faster training times, and minimal data preprocessing requirements. Traditional statistical methods also remain valuable, often serving as effective baseline models.

Key takeaways include:

- **Model Preference**: GBMs are recommended as the top off-the-shelf models for time series forecasting, while Deep Learning models are less practical and often underperform.
- **Baseline Models**: Simple statistical models should be used as starting points to gauge the added value of more complex ML models.
- **Ensembling**: Combining different models can enhance forecast accuracy, but simplicity is crucial for maintainability and explainability in production.
- **Feature Engineering**: This is more critical than model selection; effective feature creation and selection can significantly impact model performance.
- **Exogenous Variables**: Incorporating external data can greatly improve forecasting accuracy.
- **Rapid Iteration**: Quick testing of various features and models is essential for effective model development.
- **Cross-Validation**: A robust cross-validation strategy is vital for reliable model performance evaluation.
- **Unique Approaches**: Each forecasting problem requires a tailored approach rather than a one-size-fits-all solution.

The article emphasizes that while Deep Learning may evolve, it is not currently effective for practical time series forecasting tasks.
## Links

1. [Kaggle AI Report](https://kaggle.com/competitions/2023-kaggle-ai-report) - A comprehensive report that collects key learnings and trends from recent high-performing solutions in Kaggle competitions, relevant for understanding current practices in machine learning.
2. [Why You Should Always Start With a Baseline Model](https://pub.towardsai.net/why-you-should-always-start-with-a-baseline-model-95d78c70941c) - An article discussing the importance of baseline models in achieving reasonable results quickly in forecasting tasks.
3. [Accuracy competition](https://www.sciencedirect.com/science/article/pii/S0169207021001874) - A scientific article detailing the findings from the accuracy competition in the M5 forecasting challenge, highlighting effective forecasting methods.
4. [Uncertainty competition](https://www.sciencedirect.com/science/article/pii/S0169207021001722) - A scientific article that explores the uncertainty competition in the M5 challenge, focusing on probabilistic forecasting techniques.
5. [N-BEATS — The First Interpretable Deep Learning Model That Worked for Time Series Forecasting](https://towardsdatascience.com/n-beats-the-first-interpretable-deep-learning-model-that-worked-for-time-series-forecasting-06920daadac2) - An overview of the N-BEATS model, which aims to provide an interpretable approach to deep learning in time series forecasting.
## Topics

- [[topics/Model/Gradient Boosting Machines (GBMs)]]
- [[topics/Library/LightGBM]]
- [[topics/Library/XGBoost]]
- [[topics/Library/CatBoost]]
- [[topics/Concept/Feature Engineering]]