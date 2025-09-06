---
type: Concept
---

Shapley values are a method from cooperative game theory used to fairly distribute gains or costs among participants based on their contributions. In the context of machine learning, Shapley values are used to explain the output of a model by attributing the contribution of each feature to the prediction. They provide a way to understand the impact of each feature on the model's predictions, making the model more interpretable. The values are calculated by considering all possible combinations of features and measuring the marginal contribution of each feature in each combination. This method ensures that the sum of the Shapley values for all features equals the difference between the model's prediction and the base value (usually the average prediction).