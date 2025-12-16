---
already_read: true
link: https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning
read_priority: 0
relevance: 5
source: null
tags:
- Supervised_Learning
type: Content
upload_date: '2025-12-16'
---

https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-supervised-learning
## Summary

This cheatsheet provides a concise overview of supervised learning concepts, models, and algorithms, covering the following key points:

1. **Introduction to Supervised Learning**:
   - Goal: Predict outcomes (y) from input data (x) using various models.
   - Types of prediction: Regression (continuous outcomes) and Classification (discrete outcomes).
   - Types of models: Discriminative (directly estimate P(y|x)) and Generative (estimate P(x|y) to deduce P(y|x)).

2. **Notations and General Concepts**:
   - Hypothesis (h_θ): The chosen model.
   - Loss functions: Least squared error, Logistic loss, Hinge loss, Cross-entropy.
   - Cost function (J): Assesses model performance using the loss function.
   - Gradient descent: Optimizes the cost function.
   - Likelihood: Finds optimal parameters through maximization.
   - Newton's algorithm: Finds optimal parameters using derivatives.

3. **Linear Models**:
   - Linear regression: Predicts continuous outcomes using normal equations or LMS algorithm.
   - Logistic regression: Predicts discrete outcomes using the sigmoid function.
   - Softmax regression: Generalizes logistic regression for multiclass outcomes.
   - Generalized Linear Models (GLMs): Predict random variables using exponential family distributions.

4. **Support Vector Machines (SVM)**:
   - Finds the optimal margin classifier.
   - Uses hinge loss and kernel trick for non-linear classification.

5. **Generative Learning**:
   - Gaussian Discriminant Analysis (GDA): Assumes Gaussian distributions for data.
   - Naive Bayes: Assumes feature independence for classification.

6. **Trees and Ensemble Methods**:
   - CART: Decision trees for interpretable classification and regression.
   - Random forest: Ensemble of decision trees for improved performance.
   - Boosting: Combines weak learners to form a stronger one (e.g., Adaptive boosting, Gradient boosting).

7. **Other Methods**:
   - k-Nearest Neighbors (k-NN): Non-parametric approach for classification and regression.

8. **Learning Theory**:
   - Union bound, Hoeffding inequality, and PAC framework for understanding learning guarantees.
   - VC dimension: Measures the capacity of a hypothesis class.
   - Shattering: Defines when a set is shattered by a hypothesis class.
   - Upper bound theorem: Provides a bound on the expected error of a learned classifier.
## Links

- [CS 229 - Machine Learning GitHub Repository](https://github.com/afshinea/stanford-cs-229-machine-learning) : GitHub repository for Stanford's CS 229 - Machine Learning course, containing resources and materials related to machine learning.
- [Supervised Learning Cheatsheet PDF](https://github.com/afshinea/stanford-cs-229-machine-learning/blob/master/en/cheatsheet-supervised-learning.pdf) : PDF version of the Supervised Learning Cheatsheet, providing a comprehensive overview of supervised learning concepts and techniques.

## Topics

![[topics/Concept/Supervised Learning]]

![[topics/Concept/Loss Function]]

![[topics/Concept/Linear Regression]]

![[topics/Concept/Logistic Regression]]

![[topics/Concept/Support Vector Machines SVM]]

![[topics/Concept/Generative Learning]]

![[topics/Concept/Gaussian Discriminant Analysis GDA]]

![[topics/Concept/Naive Bayes]]

![[topics/Model/Random Forest]]

![[topics/Concept/Gradient Descent]]