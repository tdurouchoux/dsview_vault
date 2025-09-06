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

Quantile encoding is a variant of target encoding that uses quantiles instead of means for aggregation, making it more robust to outliers. It employs a formula that combines the quantile of a category with the overall quantile, regulated by a hyperparameter M. Key points include:

- **Formula**: \(QE_i = \dfrac{q(category_i) \cdot n_i + q(whole) \cdot M}{n_i + M}\)
- **Hyperparameters**: M (for regularization) and the chosen quantile.
- **Pros**: More resistant to outliers than target encoding.
- **Cons**: Requires tuning of hyperparameters.

The content also provides Python examples using the `category_encoders` library and the Ames dataset.
## Links

- [Quantile Encoding Issue](https://github.com/EmilHvitfeldt/feature-engineering-az/issues/40) : GitHub issue tracking the progress of implementing quantile encoding in R.
- [ColumnTransformer Documentation](https://scikit-learn.org/1.4/modules/generated/sklearn.compose.ColumnTransformer.html) : Documentation for the ColumnTransformer class in scikit-learn, used for applying different transformers to different columns in a dataset.

## Topics

![](topics/Concept/Quantile%20Encoding)