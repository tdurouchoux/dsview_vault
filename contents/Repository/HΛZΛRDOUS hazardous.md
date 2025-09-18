---
already_read: false
link: https://soda-inria.github.io/hazardous/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Statistics
- Python
type: Content
upload_date: '2025-03-25'
---

https://soda-inria.github.io/hazardous/
## Summary

Hazardous is a Python library for survival analysis and competing risks settings, focusing on time-to-event prediction. It introduces SurvivalBoost, a scalable gradient-boosting model compatible with scikit-learn. The library provides metrics like Integrated Brier Score, C-index, and Accuracy in Time for model evaluation.

Key differences:
- Survival Analysis: Predicts a single event.
- Competing Risks: Predicts multiple possible events, focusing on which event occurs first.

SurvivalBoost is designed for predictive accuracy, using a novel scoring rule to predict cumulative incidence and survival functions. It integrates with scikit-learn tools like pipelines and cross-validation. The library relies on lifelines for the Kaplan-Meier estimator and other contributions.

Note: The library does not focus on inferring statistical associations or causal effects. It is under development, and the API may change. The code is available on GitHub under the MIT license.
## Links

- [scikit-learn](https://scikit-learn.org) : scikit-learn is a Python library for machine learning, which is mentioned as being compatible with the hazardous library for survival analysis and competing risks settings.
- [lifelines](https://lifelines.readthedocs.io/en/latest/) : lifelines is a Python library for survival analysis, which is mentioned as being used by the hazardous library for the Kaplan-Meier estimator.

## Topics

![[topics/Library/lifelines)]]

![[topics/Concept/Competing Risks Setting)]]

![[topics/Library/hazardous)]]

![[topics/Model/SurvivalBoost)]]

![[topics/Concept/Survival Analysis)]]