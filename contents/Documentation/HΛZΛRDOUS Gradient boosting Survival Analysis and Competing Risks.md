---
already_read: false
link: https://soda-inria.github.io/hazardous/
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Statistics
type: Content
upload_date: '2025-03-25'
---

https://soda-inria.github.io/hazardous/
## Summary

hazardous is a Python library designed for survival analysis and competing risks, featuring a scalable gradient-boosting model called SurvivalBoost. This model is scikit-learn compatible, making it easy to integrate with existing tools.

Key features include:
- **SurvivalBoost**: A gradient-boosting method for predicting survival and competing risks, focusing on predictive accuracy over inference.
- **Performance Metrics**: Offers metrics such as Integrated Brier Score, C-index, and accuracy in time, specifically tailored for competing risks.
- **Distinction**: Unlike traditional survival analysis, competing risks consider multiple potential events, predicting which occurs first.

The library leverages lifelines for estimation and is currently under development, with an MIT license. Further theoretical details can be found in associated research.

Main contents include installation instructions, API documentation, estimators, metrics, and dataset examples.
## Links

- [Lifelines Documentation](https://lifelines.readthedocs.io/en/latest/) : Comprehensive documentation for the Lifelines library, which includes tools for survival analysis, including estimators like Kaplan-Meier and Cox model.
- [Scikit-learn Official Website](https://scikit-learn.org) : Official documentation for Scikit-learn, a machine learning library for Python, providing tools for model evaluation and selection.
- [arXiv Paper on Survival Models](https://arxiv.org/pdf/2410.16765) : Research paper discussing Survival Models with a focus on proper scoring rules and stochastic optimization in competing risks.
- [GitHub Repository for HΛZΛRDOUS](https://github.com/soda-inria/hazardous/) : The GitHub repository for the HΛZΛRDOUS library, where you can find the source code and contribute to the project.
- [Changes in HΛZΛRDOUS Library](https://github.com/soda-inria/hazardous/blob/main/CHANGES.rst) : A changelog detailing the updates and changes made to the HΛZΛRDOUS library.

## Topics

![](topics/Library/hazardous)

![](topics/Model/SurvivalBoost)

![](topics/Concept/Survival%20Analysis)

![](topics/Concept/Competing%20Risks)

![](topics/Concept/Cumulative%20Incidence%20Function)