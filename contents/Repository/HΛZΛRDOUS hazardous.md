---
already_read: false
link: https://soda-inria.github.io/hazardous/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Statistics
- Development_tool
type: Content
upload_date: '2025-03-25'
---

https://soda-inria.github.io/hazardous/
## Summary

Hazardous is a Python library for survival analysis and competing risks settings, focusing on time-to-event prediction. It introduces SurvivalBoost, a scalable gradient-boosting model compatible with scikit-learn. The library provides metrics like Integrated Brier Score, C-index, and Accuracy in Time for model evaluation.

Key differences:
- Survival Analysis: Predicts a single event.
- Competing Risks: Predicts which of multiple events will occur first.

SurvivalBoost is a gradient-boosting variant for survival and competing risks prediction, compatible with scikit-learn tools. It predicts the cumulative incidence function and survival function at any horizon, with a focus on predictive accuracy. The library relies on lifelines for the Kaplan-Meier estimator and other contributions.

Note: The library does not currently support quantifying the statistical association or causal effect of covariates on the cumulative event incidence or instantaneous hazard rate. The API is under development and subject to change. The library is licensed under MIT.
## Links

- [Hazardous GitHub Repository](https://github.com/soda-inria/hazardous) : The GitHub repository for the Hazardous library, providing access to the source code, issues, and project updates.
- [Lifelines Documentation](https://lifelines.readthedocs.io/en/latest/) : Documentation for the Lifelines library, which provides tools for survival analysis, including the Kaplan-Meier estimator and Cox model.
- [Survival Models Research Paper](https://arxiv.org/pdf/2410.16765) : Research paper detailing the theoretical background and stochastic optimization methods used in SurvivalBoost.

## Topics

![](topics/Library/hazardous)

![](topics/Concept/SurvivalBoost)

![](topics/Concept/Survival%20Analysis)

![](topics/Concept/Competing%20Risks)

![](topics/Library/lifelines)