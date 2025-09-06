---
already_read: false
link: https://www.pymc-labs.com/blog-posts/probabilistic-forecasting/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Time_Series
- Statistics
type: Content
upload_date: '2025-05-21'
---

https://www.pymc-labs.com/blog-posts/probabilistic-forecasting/
## Summary

The post discusses the advantages of probabilistic forecasting models over traditional time series methods in business applications. Key points include:

1. **Hierarchical Models**: These models improve forecasting by sharing information across related time series, particularly useful for sparse data. They outperform independent models by capturing shared trends and seasonality.

2. **Censored Likelihoods**: These models address data censoring issues, such as stockouts in retail, by accurately modeling underlying demand even when observations are truncated. This leads to better inventory planning and revenue optimization.

3. **Availability-Constrained TSB Models**: For intermittent demand patterns, these models distinguish between true zero demand and stockout-induced zeros, providing more accurate forecasts for sporadically selling products.

4. **Calibration and Custom Likelihoods**: Incorporating domain knowledge through model calibration enhances forecasting accuracy, especially in scenarios with limited historical data or unobserved confounders.

5. **Hierarchical Price Elasticity Models**: Bayesian hierarchical models improve price elasticity estimates in retail settings by leveraging multilevel data structures, providing more stable and economically sensible estimates.

6. **State Space Models in PyMC**: These models offer a flexible and interpretable framework for time series forecasting, capable of handling complex dynamics and incorporating domain knowledge through informative priors.

The post concludes that probabilistic forecasting models not only quantify uncertainty more effectively but also enable the incorporation of business constraints and domain knowledge, leading to more actionable and interpretable forecasts. These models are becoming increasingly accessible and valuable for modern data scientists.
## Links

- [Hierarchical Modeling](https://betanalpha.github.io/assets/case_studies/hierarchical_modeling.html) : A detailed write-up on hierarchical modeling, explaining how information sharing across related groups can improve model performance through regularization.
- [Quarterly Tourism in Australia Dataset](https://www.kaggle.com/datasets/luisblanche/quarterly-tourism-in-australia) : A dataset containing tourism volumes in Australia between 1998 and 2016, categorized by state, region, and purpose.
- [Demand Forecasting with Censored Likelihood](https://juanitorduz.github.io/demand/) : A simulation study demonstrating how Bayesian models with censored likelihoods can provide more accurate demand forecasts compared to traditional time series methods.
- [Availability-Constrained TSB Models](https://juanitorduz.github.io/availability_tsb/) : A case study on extending the TSB model to account for availability constraints in intermittent demand forecasting.
- [Electricity Demand Forecast with Prior Calibration](https://juanitorduz.github.io/electricity_forecast_with_priors/) : A case study on incorporating external information to improve a dynamic time-series model for electricity demand forecasting.

## Topics

![](topics/Concept/Probabilistic%20Forecasting)

![](topics/Concept/Hierarchical%20Models)

![](topics/Concept/Censored%20Likelihoods)

![](topics/Concept/Availability%20Constrained%20TSB%20Models)

![](topics/Concept/Calibration%20and%20Custom%20Likelihoods)

![](topics/Concept/Hierarchical%20Price%20Elasticity%20Models)

![](topics/Concept/State%20Space%20Models)