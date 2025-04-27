---
already_read: false
link: https://www.aidancooper.co.uk/how-shapley-values-work/
read_priority: 1
relevance: 0
source: null
tags:
- Model_evaluation
type: Content
upload_date: '2023-01-12'
---

https://www.aidancooper.co.uk/how-shapley-values-work/
## Summary

Shapley values are a method used in machine learning for explainability, helping quantify each feature's contribution to a model's predictions. This article provides a straightforward approach to understanding Shapley values using code and simplified examples.

Key points include:

- **Dataset Overview**: The article uses a modified Boston housing dataset with three features: percentage of working class, number of rooms, and NOX concentration, to predict house prices.
  
- **Shapley Value Calculation**: The mechanics involve determining how much each feature contributes to the model's prediction for a specific instance by analyzing all possible combinations of feature coalitions. The final Shapley values are derived from the weighted sum of marginal contributions from these combinations.

- **Base Value and Prediction Breakdown**: The total prediction can be expressed as the sum of a base value and the contributions (or Shapley values) of each feature. 

- **Difference Between Shapley and SHAP**: Shapley values require significant computational time (2^F retrains for F features), whereas SHAP (SHapley Additive exPlanations) provides approximation strategies to mitigate this issue.

- **Visualization Techniques**: The article discusses several ways to visualize Shapley values, including waterfall charts for individual predictions and bar charts showing the mean absolute contributions of features, revealing insights about their overall importance.

- **Conclusion**: The article highlights the value of calculating and visualizing Shapley values for interpreting machine learning model predictions, and indicates a forthcoming discussion on SHAP's approximation techniques for broader applications.
## Links

- [SHAP Documentation](https://shap.readthedocs.io/en/latest/?xgtab=&ref=aidancooper.co.uk) : Official documentation for the SHAP library, which provides an overview of SHAP values and how to implement them in machine learning.
- [Aidan Cooper's GitHub Repository](https://github.com/AidanCooper/shapley-values-from-scratch/?xgtab=&ref=aidancooper.co.uk) : A collection of code samples for calculating Shapley values from scratch, accompanying Aidan Cooper's article.
- [US National Library of Medicine Paper on Shapley Values](https://proceedings.neurips.cc/paper/2017/file/8a20a8621978632d76c43dfd28b67767-Paper.pdf?xgtab=&ref=aidancooper.co.uk) : Research paper discussing the theoretical foundations and applications of Shapley values in machine learning.
- [Seaborn Visualization Library](https://seaborn.pydata.org/?xgtab=&ref=aidancooper.co.uk) : Seaborn is a Python data visualization library based on matplotlib, used for making statistical graphics.
- [LIME GitHub Repository](https://github.com/marcotcr/lime?xgtab=&ref=aidancooper.co.uk) : GitHub repository for LIME (Local Interpretable Model-agnostic Explanations), a tool for interpretability in machine learning models.

## Topics

![](topics/Concept/Shapley%20Values)

![](topics/Concept/SHAP)

![](topics/Dataset/Boston%20Housing%20Dataset)

![](topics/Library/scikit%20learn)

![](topics/Library/pandas)

![](topics/Library/Plotly)

![](topics/Library/Seaborn)