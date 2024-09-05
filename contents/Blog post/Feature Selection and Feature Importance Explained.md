---
already_read: false
link: https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
read_priority: 1
source: null
tags:
- Feature_Engineering
type: Content
upload_date: '2023-04-06'
---

https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
## Summary

Feature selection and feature importance are distinct yet complementary processes in machine learning. Feature selection aims to reduce the dimensionality of the input feature space to improve model performance, speed, and comprehensibility. It can be performed using various methods, including filter methods, model constraints, and wrapper methods.

In contrast, feature importance focuses on ranking and quantifying the contribution of each feature to model predictions. This can be achieved through methods like regression coefficients, permutation feature importance, and SHAP values. Understanding feature importance helps in model auditing, debugging, and feature engineering.

While both processes can enhance interpretability, they should be treated as separate steps. Feature selection can simplify interpretation by reducing the number of features, while feature importance can inform qualitative decisions about feature relevance. However, it is advised not to rely solely on feature importance for feature selection due to potential model-specific biases and issues with correlated features.
## Links

1. [Interpretable Machine Learning](https://christophmolnar.com/books/interpretable-machine-learning/) - A comprehensive resource on methods for interpreting machine learning models, including feature importance techniques.
2. [Correlation Can Ruin Interpretability](https://mindfulmodeler.substack.com/p/correlation-can-ruin-interpretability) - An article discussing how correlated features can negatively impact the interpretability of machine learning models.
## Topics

- [[topics/Concept/Feature Selection]]
- [[topics/Concept/Feature Importance and Interpretability]]
- [[topics/Concept/Permutation Feature Importance]]
- [[topics/Concept/LASSO]]
- [[topics/Concept/SHAP and Feature Importance]]