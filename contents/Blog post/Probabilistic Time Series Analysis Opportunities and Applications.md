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

The blog post discusses the advantages of probabilistic forecasting models over traditional time series methods in business applications. Key points include:

1. **Hierarchical Models**: These models improve forecasting by sharing information across related time series, enhancing performance, especially for smaller areas or less frequent data points. An example with tourism data in Australia shows how hierarchical exponential smoothing can capture shared trends better than independent models.

2. **Censored Likelihoods**: In demand forecasting, censored data (where values are partially known due to stockouts or capacity constraints) can be accurately modeled using Bayesian methods. This approach provides more accurate demand forecasts by reconstructing the true demand distribution, which is crucial for inventory planning and revenue optimization.

3. **Availability-Constrained TSB Models**: For intermittent time series common in retail, the Teunter-Syntetos-Babai (TSB) model can be extended to account for product availability. This modification distinguishes between true zero demand and zeros caused by unavailability, leading to more accurate forecasts for sporadically selling products.

4. **Calibration and Custom Likelihoods**: Domain knowledge can be incorporated into probabilistic models through calibration. For example, electricity demand forecasting can be improved by modeling the relationship between temperature and demand, with constraints on extreme temperatures to produce more reliable forecasts.

5. **Hierarchical Price Elasticity Models**: Bayesian hierarchical models improve price elasticity estimates in retail settings by leveraging the multilevel structure of retail data. This approach produces more stable and economically sensible elasticity estimates, especially for products with limited price variation or sparse sales data.

6. **State Space Models in PyMC**: The PyMC-Extras module provides a flexible framework for building sophisticated forecasting models using state space representations. These models can handle complex dynamics, including time-varying trends, multiple seasonality patterns, and external regressors, while maintaining interpretability.

The post concludes that probabilistic forecasting models offer significant advantages by incorporating business constraints, domain knowledge, and potentially causal relationships, leading to more accurate and actionable forecasts. These models are becoming increasingly accessible and valuable for modern data scientists.
## Links

- [Nixtla GitHub](https://github.com/Nixtla) : GitHub repository for Nixtla, which develops open-source packages for time series forecasting, including statsforecast and mlforecast.
- [Quarterly Tourism in Australia Dataset](https://www.kaggle.com/datasets/luisblanche/quarterly-tourism-in-australia) : Dataset containing quarterly tourism volumes in Australia, used for illustrating hierarchical forecasting models.
- [Hierarchical Modeling Case Study](https://betanalpha.github.io/assets/case_studies/hierarchical_modeling.html) : Detailed write-up on hierarchical modeling, explaining how information sharing across related groups can improve model performance.
- [Demand Forecasting with Censored Likelihood](https://juanitorduz.github.io/demand/) : Simulation study demonstrating how Bayesian models with censored likelihoods can provide more accurate demand forecasts compared to traditional time series methods.
- [Availability-Constrained TSB Models](https://juanitorduz.github.io/availability_tsb/) : Case study on extending the TSB model to account for availability constraints in intermittent demand forecasting.

## Topics

![[topics/Library/PyMC]]

![[topics/Concept/Censored Likelihoods]]

![[topics/Concept/Calibration and Custom Likelihoods]]

![[topics/Concept/Hierarchical Price Elasticity Models]]

![[topics/Concept/Hierarchical Models]]

![[topics/Concept/State Space Models]]

![[topics/Concept/Availability Constrained TSB Models]]

![[topics/Concept/Probabilistic Forecasting]]