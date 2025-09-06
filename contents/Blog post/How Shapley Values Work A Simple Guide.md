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

Shapley values are a machine learning explainability technique that quantifies the contribution of each feature to a model's prediction. The article explains Shapley values using a simplified Boston housing dataset with three features: % working class, number of rooms, and NOX concentration. The mechanics of Shapley values involve considering all possible combinations of features (the power set) and calculating the marginal contributions of each feature to the model's predictions. The Shapley value for a feature is then calculated as a weighted sum of these marginal contributions. The article also distinguishes between Shapley values and SHAP values, noting that SHAP is a more efficient approximation of Shapley values. The article provides a worked example of calculating Shapley values for a random forest regressor trained on the Boston housing dataset. It includes code for retraining the model for each feature coalition, calculating the Shapley values, and visualizing them using waterfall charts, bar charts, and beeswarm plots. The article concludes by discussing the insights that can be gained from these visualizations and mentions a future post on SHAP.
## Links

- [Plotly](https://plotly.com/?xgtab=&ref=aidancooper.co.uk) : Plotly is a graphing library making interactive, publication-quality graphs online.
- [LIME](https://github.com/marcotcr/lime) : LIME is a technique that explains the predictions of any machine learning classifier in an interpretable and faithful manner, by approximating it locally with an interpretable model.
- [SHAP](https://github.com/slundberg/shap) : SHAP (SHapley Additive exPlanations) is a unified method to explain the output of any machine learning model. SHAP connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related concepts (e.g. Shapley interactions). This method assigns each feature an importance value for a particular prediction.

## Topics

![](topics/Concept/Shapley%20Values)

![](topics/Concept/SHAP)

![](topics/Concept/Explainable%20AI)

![](topics/Model/Random%20Forest)

![](topics/Concept/Waterfall%20Chart)

![](topics/Concept/Beeswarm%20Plot)