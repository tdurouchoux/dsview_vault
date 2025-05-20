---
already_read: false
link: https://www.pymc-labs.com/blog-posts/probabilistic-forecasting/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Time_Series
type: Content
upload_date: '2025-05-21'
---

https://www.pymc-labs.com/blog-posts/probabilistic-forecasting/
## Summary

The article discusses the transformative potential of Bayesian methods in probabilistic time series forecasting, emphasizing their advantages over traditional point forecasts, particularly in uncertain and complex environments.

Key points include:

1. **Probabilistic Forecasting Advantages**: Unlike point forecasts, probabilistic models provide complete probability distributions for future outcomes, aiding in better decision-making by incorporating uncertainty.

2. **Classical vs. Probabilistic Models**: Traditional forecasting methods (e.g., exponential smoothing, ARIMA) can capture some trends but may miss critical uncertainties. Bayesian models allow joint modeling of mean and variance, enhancing flexibility.

3. **Hierarchical Models**: These models leverage shared information across related groups (e.g., subcategories or regions) to improve forecasting accuracy, particularly when data is sparse.

4. **Censored Likelihoods**: In demand forecasting, Bayesian models with censored data can better predict true demand during stockouts by reconstructing underlying distributions, addressing limitations of typical methods.

5. **Intermittent Demand**: The Teunter-Syntetos-Babai (TSB) model can be adapted to account for availability constraints, distinguishing between true demand and stockout situations.

6. **Calibration and Custom Likelihoods**: Incorporating domain knowledge can refine model forecasts; case studies show how prior calibration improves predictions in contexts like electricity demand forecasting.

7. **Price Elasticity Models**: Hierarchical Bayesian models enhance price sensitivity analysis, allowing for robust estimates across product categories, overcoming challenges related to sparse sales data.

8. **State Space Models in PyMC**: New tools in PyMC facilitate complex dynamics modeling in time series, offering flexibility and interpretability for business applications.

Overall, the article asserts that probabilistic forecasting allows for more accurate, actionable insights by integrating business constraints and expert knowledge, underscoring its growing importance in data science.
## Links

- [DeepAR: Probabilistic Forecasting with Autoregressive Recurrent Networks](https://arxiv.org/abs/1704.04110) : A research paper introducing DeepAR, a probabilistic forecasting model developed by Amazon that utilizes autoregressive recurrent networks.
- [Hierarchical Exponential Smoothing](https://juanitorduz.github.io/hierarchical_exponential_smoothing/) : A resource detailing how to implement hierarchical exponential smoothing models for time series forecasting.
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/) : An open textbook providing a comprehensive introduction to forecasting methods and principles.
- [Demand Forecasting with Censored Likelihood](https://juanitorduz.github.io/demand/) : A case study demonstrating the effectiveness of Bayesian models with censored likelihoods in demand forecasting.
- [Hierarchical Modeling Case Studies](https://betanalpha.github.io/assets/case_studies/hierarchical_modeling.html) : A collection of case studies exploring hierarchical modeling techniques in various applications.

## Topics

![](topics/Concept/Probabilistic%20Forecasting)

![](topics/Library/PyMC)

![](topics/Model/Hierarchical%20Models)

![](topics/Model/Censored%20Likelihood%20Models)

![](topics/Concept/Availability%20Constrained%20Forecasting)

![](topics/Model/Teunter%20Syntetos%20Babai%20TSB%20Model)

![](topics/Concept/Parameter%20Calibration)

![](topics/Platform/NumPyro)

![](topics/Concept/State%20Space%20Models)