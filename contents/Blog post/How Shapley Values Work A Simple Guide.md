---
already_read: false
link: https://www.aidancooper.co.uk/how-shapley-values-work/
read_priority: 1
relevance: 0
source: null
tags:
- Supervised_Learning
- Model_evaluation
type: Content
upload_date: '2023-01-12'
---

https://www.aidancooper.co.uk/how-shapley-values-work/
## Summary

The article explains Shapley values, a machine learning explainability technique, using a simplified Boston housing dataset with three features: % working class, number of rooms, and NOX concentration. Shapley values quantify the contribution of each feature to a model's prediction. The process involves retraining the model for all possible feature coalitions (power set) and calculating the marginal contributions of each feature. The Shapley value for a feature is the weighted sum of its marginal contributions. The article also distinguishes Shapley values from SHAP values, noting that SHAP uses approximation methods for efficiency. The practical implementation involves retraining a random forest model for each feature coalition, calculating Shapley values, and visualizing them using waterfall charts, bar charts, and beeswarm plots. The visualizations help understand local and global feature importance. The article concludes by mentioning a future post on SHAP.
## Links

- [Shapley Values from Scratch GitHub Repository](https://github.com/AidanCooper/shapley-values-from-scratch/?xgtab=&ref=aidancooper.co.uk) : GitHub repository containing code samples for calculating Shapley values from scratch, as demonstrated in the article.
- [SHAP Documentation](https://shap.readthedocs.io/en/latest/?xgtab=&ref=aidancooper.co.uk) : Official documentation for SHAP (SHapley Additive exPlanations), a popular library for interpreting machine learning models using Shapley values.

## Topics

![](topics/Concept/Shapley%20Values)

![](topics/Concept/SHAP%20SHapley%20Additive%20exPlanations)

![](topics/Concept/Explainable%20AI)

![](topics/Dataset/Boston%20housing%20dataset)

![](topics/Library/scikit%20learn)