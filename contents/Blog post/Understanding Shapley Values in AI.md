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

- **Dataset Overview**: The dataset includes features such as the percentage of working-class population, number of rooms, and NOX concentration, used to predict house prices.

- **Mechanics of Shapley Values**: For a given instance, Shapley values express the predicted price as a sum of a base value and the contributions from each feature. The contributions are derived from the marginal effects of adding each feature to the model, considering all possible combinations of features.

- **Calculating Shapley Values**: The article details the process of retraining the model for every possible combination of features (the power set) and calculating the Shapley values as a weighted sum of marginal contributions.

- **SHAP vs. Shapley Values**: While Shapley values require extensive computation, SHAP (SHapley Additive exPlanations) provides efficient approximations, especially for tree-based models, making it more practical for real-world applications.

- **Visualization**: The article demonstrates how to visualize Shapley values using waterfall charts and beeswarm plots to gain insights into feature importance and their effects on predictions.

- **Conclusion**: The article emphasizes the importance of understanding Shapley values for model interpretability and hints at future discussions on SHAP for approximating these values in machine learning contexts.
## Links

1. [SHAP](https://shap.readthedocs.io/en/latest/?xgtab=&amp;ref=aidancooper.co.uk) - Documentation for SHAP, a library for interpreting machine learning models using Shapley values.
2. [Boston housing dataset](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html?xgtab=&amp;ref=aidancooper.co.uk) - Detailed information about the Boston housing dataset used in the Shapley values example.
3. [LIME](https://github.com/marcotcr/lime?xgtab=&amp;ref=aidancooper.co.uk) - GitHub repository for LIME, a technique for model interpretability that can be used alongside SHAP.
4. [Approximating Shapley Values for Machine Learning](https://www.aidancooper.co.uk/approximating-shapley-values/) - An article explaining how to approximate Shapley values for machine learning models.
5. [GitHub - AidanCooper/shapley-values-from-scratch](https://github.com/AidanCooper/shapley-values-from-scratch/?xgtab=&amp;ref=aidancooper.co.uk) - GitHub repository containing code samples for calculating Shapley values from scratch.
## Topics

- [[topics/Concept/Shapley Values]]
- [[topics/Concept/SHAP and Feature Importance]]
- [[topics/Library/scikit-learn]]
- [[topics/Library/pandas]]
- [[topics/Library/Plotly]]