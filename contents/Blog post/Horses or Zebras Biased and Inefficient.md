---
already_read: true
link: https://notstatschat.rbind.io/2025/12/01/horses-or-zebras/
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Statistics
- Supervised_Learning
type: Content
upload_date: '2026-01-04'
---

https://notstatschat.rbind.io/2025/12/01/horses-or-zebras/
## Summary

The text discusses the issue of class imbalance in predictive modeling, using the metaphor of predicting horses versus zebras. Key points include:

1. **Class Imbalance**: Many predictive techniques struggle with imbalanced data, where one class (e.g., \(Y=0\)) dominates. This leads to high negative predictive value but low positive predictive value and sensitivity.

2. **Reasons for Adjustment**: There are two main reasons to adjust for class imbalance:
   - The prior probability of the minority class (\(Y=1\)) in production is higher than in the training data.
   - The cost of false negatives is higher than false positives.

3. **Adjustment Methods**:
   - **Prior Probability Adjustment**: Use Bayes' Theorem to adjust the decision threshold, especially relevant when applying a model trained on a case-control sample to a population with a different class distribution.
   - **Penalty Adjustment**: Incorporate different penalties for false positives and false negatives into the objective function during model fitting.

4. **Logistic Regression**: In logistic regression, adjusting prior probabilities or penalties changes the intercept or decision threshold. Oversampling cases can also achieve similar results.

5. **Generalization to Other Models**: The principles apply to other binary prediction techniques that minimize additive loss. Different prior probabilities can be handled with prior-probability weights, and different penalties can be managed by considering the two possible losses for each prediction.

6. **Oversampling vs. Weighting**: Oversampling is a form of case weighting but may not be ideal for uncertainty estimation. Weighting is more accurate as it describes the scenario more precisely.

The text emphasizes that addressing class imbalance should be driven by the specific problem context and the relative costs of different types of errors.
## Links

- [GitHub Repository](https://github.com/tslumley/notstatschat) : GitHub repository for the blog post author, potentially containing additional code, data, or resources related to the discussed topics.

## Topics

![[topics/Concept/Class Imbalance]]

![[topics/Concept/Bayes Theorem]]

![[topics/Concept/Case Control Sampling]]

![[topics/Concept/Logistic Regression]]