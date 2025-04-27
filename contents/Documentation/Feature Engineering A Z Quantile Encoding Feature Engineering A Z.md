---
already_read: false
link: https://feaz-book.com/categorical-quantile
read_priority: 1
relevance: 0
source: null
tags:
- Feature_Engineering
type: Content
upload_date: '2024-03-14'
---

https://feaz-book.com/categorical-quantile
## Summary

Quantile Encoding is a method for encoding categorical features, offering a robust alternative to traditional target encoding by utilizing quantiles instead of means for aggregation. This method helps mitigate the effects of outliers, especially with quantiles that are not at the extremes.

Key aspects include:
- **Formula**: The quantile encoding value is calculated using a combination of the quantile of the category, the quantile of the whole dataset, the number of observations in the category, and a regularization hyperparameter \(M\). The formula is:
  \[
  QE_i = \dfrac{q(category_i) \cdot n_i + q(whole) \cdot M}{n_i + M}
  \]
- **Pros**: Less susceptible to the influence of outliers when compared to target encoding.
- **Cons**: Requires tuning of hyperparameters, specifically \(M\) and the choice of quantile, which may lead to trade-offs between computational cost and performance.

Examples in Python using the `category_encoders` library show how to implement Quantile Encoding with the Ames dataset, utilizing a `ColumnTransformer` to integrate the encoded feature into a broader dataset context.
## Links

- [Quantile Encoder Issue Tracker](https://github.com/EmilHvitfeldt/feature-engineering-az/issues/40) : Tracker for issues related to the implementation of quantile encoding in a feature engineering library.
- [ColumnTransformer Documentation](https://scikit-learn.org/1.4/modules/generated/sklearn.compose.ColumnTransformer.html) : Official documentation for the ColumnTransformer class in scikit-learn, which is useful for preprocessing data.
- [Feature Engineering A-Z GitHub Repository](https://github.com/EmilHvitfeldt/feature-engineering-az) : Official GitHub repository for the Feature Engineering A-Z project, including various encoding techniques.

## Topics

![](topics/Concept/Quantile%20Encoding)

![](topics/Library/category_encoders)

![](topics/Concept/Hyperparameter%20Optimization)

![](topics/Concept/Outlier%20Robustness)