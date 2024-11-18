---
already_read: false
link: https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
read_priority: 1
source: null
tags:
- Feature_Engineering
- Data_Quality
type: Content
upload_date: '2023-04-06'
---

https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
## Summary

Feature selection and feature importance are distinct yet complementary processes in machine learning. Feature selection aims to reduce the dimensionality of the input feature space to improve model performance, speed, and interpretability. It can be performed using various methods, including filter methods, model constraints, and wrapper methods.

In contrast, feature importance focuses on ranking and quantifying the contribution of each feature to model predictions. This can be achieved through methods like regression coefficients, permutation feature importance, and SHAP values. Understanding feature importance helps in model auditing, debugging, and feature engineering.

While both processes can enhance each other—feature selection can simplify interpretation, and insights from feature importance can inform selection—they should be treated as separate steps. Feature selection is typically automated and occurs before or during model training, while feature interpretation is a more manual, post-hoc analysis. The author advises against using feature importance measures directly for feature selection, as there are more reliable methods for that purpose.
## Links

1. [Interpretable Machine Learning](https://christophmolnar.com/books/interpretable-machine-learning/) - A comprehensive resource on methods for interpreting machine learning models, including feature importance techniques.
2. [Correlation Can Ruin Interpretability](https://mindfulmodeler.substack.com/p/correlation-can-ruin-interpretability) - An article discussing how correlation among features can impact the interpretability of machine learning models.
## Topics

![](topics/Concept/Feature%20Selection)

![](topics/Concept/Feature%20Importance)

![](topics/Concept/Permutation%20Feature%20Importance)

![](topics/Concept/LASSO)

![](topics/Concept/SHAP%20Shapley%20Additive%20Explanations)