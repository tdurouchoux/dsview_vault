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

Feature selection and feature importance are distinct but complementary steps in machine learning, each with different goals. Feature selection aims to reduce the dimensionality of the input feature space to improve predictive performance, speed up training, reduce costs, or enhance comprehensibility. Methods include filter, wrapper, and embedded techniques like L1 regularization. Feature importance, on the other hand, ranks and quantifies the contribution of features to model predictions or performance, aiding in model understanding, auditing, debugging, and feature engineering.

While feature selection can aid interpretation by reducing the number of features and removing correlated ones, feature importance can inform qualitative decisions about feature removal. However, it's not recommended to directly use feature importance measures for feature selection, as there are dedicated methods for selecting non-performing features. Both steps should be treated as separate but related processes in the modeling pipeline.
## Links

- [Interpretable Machine Learning](https://christophmolnar.com/books/interpretable-machine-learning/) : A book by Christoph Molnar providing an overview of feature importance methods and other interpretation tools for machine learning models.

## Topics

![](topics/Concept/Feature%20Importance)

![](topics/Concept/Permutation%20Feature%20Importance)

![](topics/Concept/SHAP%20SHapley%20Additive%20exPlanations)

![](topics/Concept/Feature%20Selection)

![](topics/Concept/LASSO%20Least%20Absolute%20Shrinkage%20and%20Selection%20Operator)