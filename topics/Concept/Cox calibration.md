---
type: Concept
---

A method for assessing the calibration of a binary classification model by fitting a logistic regression model where the predicted probabilities are the independent variable and the true labels are the dependent variable. The intercept and slope of the fitted model indicate calibration: an intercept close to 0 and a slope close to 1 suggest good calibration. Bias is reflected in the intercept, while miscalibration (e.g., overconfidence or underconfidence) is reflected in the slope.