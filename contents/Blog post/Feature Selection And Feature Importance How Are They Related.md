---
already_read: false
link: https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
read_priority: 1
relevance: 0
source: null
tags:
- Feature_Engineering
type: Content
upload_date: '2023-04-06'
---

https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
## Summary

Feature selection and feature importance are distinct yet complementary aspects of machine learning. Feature selection aims to reduce the dimensionality of the input feature space to improve model predictive performance, speed up training, enhance comprehensibility, and lower costs. Methods include filter methods, model constraints like LASSO, and wrapper methods. This process typically occurs before or during model training.

On the other hand, feature importance focuses on ranking and quantifying the contribution of features to model predictions. It helps in understanding model behavior, auditing, debugging, and improving feature engineering. Methods for determining feature importance vary, including regression coefficients, permutation feature importance, and SHAP values.

While both processes can inform each other, they should be treated separately. Effective feature selection can simplify interpretation, while insights from feature importance can guide qualitative decisions during feature selection. However, it's generally not recommended to use feature importance measures directly for selecting features due to potential model-specific biases and issues with correlated features.
## Links

- [Interpretable Machine Learning Book by Christoph Molnar](https://christophmolnar.com/books/interpretable-machine-learning/) : A book that provides a comprehensive overview of various interpretability methods in machine learning, including feature importance.
- [Correlation Can Ruin Interpretability](https://mindfulmodeler.substack.com/p/correlation-can-ruin-interpretability) : An article discussing how correlation between features can affect model interpretability and recommendations to mitigate these issues.

## Topics

![](topics/Concept/Feature%20Selection)

![](topics/Concept/Feature%20Importance%20Analysis)

![](topics/Model/LASSO%20Regression)

![](topics/Concept/Permutation%20Feature%20Importance)

![](topics/Concept/SHAP)