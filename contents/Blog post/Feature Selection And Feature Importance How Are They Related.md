---
already_read: false
link: https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
read_priority: 1
relevance: 0
source: null
tags:
- Feature_Engineering
- Model_evaluation
type: Content
upload_date: '2023-04-06'
---

https://mindfulmodeler.substack.com/p/feature-selection-or-feature-importance
## Summary

Feature selection and feature importance are distinct but complementary steps in machine learning, each with unique goals. Feature selection aims to reduce the dimensionality of the input feature space, improving predictive performance, speeding up model training, and enhancing comprehensibility. Methods range from filter methods to wrapper methods and internal model constraints. On the other hand, feature importance seeks to rank and quantify the contribution of features to model predictions and performance, aiding in model understanding, auditing, debugging, and feature engineering.

While feature selection is typically an automated pre-processing step, feature importance is a more hands-on post-hoc step. However, they are related: effective feature selection can simplify interpretation by reducing the number of features and removing correlated ones. Conversely, feature importance can inform qualitative decisions about feature removal, though it is not recommended for direct feature selection due to potential model-specific biases and issues with correlated features. The author advises treating these steps separately but leveraging their interplay for better model performance and interpretability.
## Links

- [Interpretable Machine Learning Book](https://christophmolnar.com/books/interpretable-machine-learning/) : A book by Christoph Molnar providing an overview of feature importance methods and other interpretation tools for machine learning models.

## Topics

![](topics/Concept/Permutation%20Feature%20Importance)

![](topics/Concept/LASSO%20Least%20Absolute%20Shrinkage%20and%20Selection%20Operator)