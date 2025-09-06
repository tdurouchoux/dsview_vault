---
type: Concept
---

Quantile encoding is a technique used for encoding categorical features by replacing categories with quantiles of a target variable. It is a reimagined version of target encoding and M-estimator encoding that uses quantiles instead of means and M regularization from M-estimator. Quantile encoding is generally more robust to outliers for quantiles away from the end. It is suggested to be paired with M-estimator style regularization to deal with the issue of having smaller groups. The technique involves two hyperparameters: M, which needs to be tuned, and the choice of quantile, which can be set to specific values or tuned for better results.