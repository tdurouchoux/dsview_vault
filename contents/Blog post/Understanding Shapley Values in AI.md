---
already_read: false
link: https://www.aidancooper.co.uk/how-shapley-values-work/
read_priority: 1
source: null
type: Content
upload_date: '2023-01-12'
---

https://www.aidancooper.co.uk/how-shapley-values-work/
## Summary

Shapley values are a method for explaining the predictions of machine learning models by quantifying the contribution of each feature to a specific prediction. This article uses a simplified version of the Boston housing dataset to illustrate how to calculate Shapley values from scratch.

Key points include:

- **Dataset Overview**: The dataset contains house prices and three features: percentage of working class, number of rooms, and NOX concentration.
  
- **Mechanics of Shapley Values**: For a given instance, Shapley values express the predicted price as a sum of a base value and the contributions from each feature. The contributions are derived from the marginal effects of adding each feature to the model, considering all possible combinations of features.

- **Calculating Shapley Values**: The article details the process of retraining the model for every possible combination of features (the power set) and calculating the Shapley values as a weighted sum of marginal contributions.

- **SHAP vs. Shapley Values**: SHAP (SHapley Additive exPlanations) is an extension of Shapley values that uses approximation methods to make calculations more efficient, especially for complex models.

- **Visualization**: The article demonstrates how to visualize Shapley values using waterfall charts and beeswarm plots to gain insights into feature importance and their effects on predictions.

- **Conclusion**: The article emphasizes the importance of understanding Shapley values for model interpretability and hints at future discussions on approximating Shapley values for practical applications in machine learning.
## Links

1. [SHAP Documentation](https://shap.readthedocs.io/en/latest/?xgtab=&ref=aidancooper.co.uk) - Official documentation for SHAP, a library for interpreting machine learning models using Shapley values.
2. [LIME GitHub Repository](https://github.com/marcotcr/lime?xgtab=&ref=aidancooper.co.uk) - GitHub repository for LIME, a technique for model interpretability that can be used alongside SHAP.
3. [SHAP GitHub Repository](https://github.com/slundberg/shap?xgtab=&ref=aidancooper.co.uk) - GitHub repository for the SHAP library, which provides implementations for calculating Shapley values.
4. [NeurIPS Paper on Shapley Values](https://proceedings.neurips.cc/paper/2017/file/8a20a8621978632d76c43dfd28b67767-Paper.pdf?xgtab=&ref=aidancooper.co.uk) - A foundational paper discussing the theory and application of Shapley values in machine learning.
5. [Boston Housing Dataset](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html?xgtab=&ref=aidancooper.co.uk) - Detailed information about the Boston housing dataset used in many machine learning examples, including Shapley value calculations.
## Topics

![](topics/Concept/Shapley%20Values)

![](topics/Concept/SHAP)

![](topics/Dataset/Boston%20Housing%20Dataset)

![](topics/Library/scikit%20learn)

![](topics/Library/Plotly)