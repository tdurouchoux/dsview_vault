---
already_read: false
link: https://www.amazon.science/blog/introducing-chronos-2-from-univariate-to-universal-forecasting
read_priority: 5
relevance: 0
source: Data Points
tags:
- Time_Series
type: Content
upload_date: '2025-11-26'
---

https://www.amazon.science/blog/introducing-chronos-2-from-univariate-to-universal-forecasting
## Summary

The article introduces Chronos-2, a universal time series forecasting model developed by Amazon. Chronos-2 is designed to handle various forecasting tasks, including univariate, multivariate, and covariate-informed forecasting, in a zero-shot manner using in-context learning (ICL). This model represents a significant advancement over previous time series foundation models (TSFMs) like Chronos and Chronos-Bolt, which were limited to univariate forecasting.

Key features and innovations of Chronos-2 include:

1. **In-Context Learning (ICL)**: Enables the model to perform forecasting tasks without additional training, making it versatile for different forecasting scenarios.
2. **Multivariate Forecasting**: Can jointly predict multiple coevolving time series, capturing dependencies that improve overall accuracy.
3. **Covariate-Informed Forecasting**: Incorporates external factors that influence predictions, such as past-only covariates, known future covariates, and categorical covariates.
4. **Cross-Learning**: Improves univariate forecasting by sharing information across univariate time series, which is particularly valuable for cold-start scenarios.
5. **Architectural Innovations**: The model uses a group attention mechanism to account for interactions between variables in unseen tasks, and it is trained on heterogeneous time series tasks using synthetic data.

Empirical evaluations show that Chronos-2 outperforms existing TSFMs on comprehensive benchmarks like fev-bench and GIFT-Eval, demonstrating significant gains, especially on covariate-informed tasks. Chronos-2 is now available open source, inviting researchers and practitioners to engage with and further develop the model.

The article also highlights related content and research areas, including adapting language model architectures for time series forecasting, the role of foundation models in scientific domains, and the practical applications of deep learning in Earth system forecasting. Additionally, it mentions various career opportunities and research collaborations within Amazon.
## Links

- [Chronos-2 model card](https://huggingface.co/amazon/chronos-2) : The model card for Chronos-2, providing detailed information about the model's capabilities, usage, and performance.
- [Deploy Chronos-2 on Amazon SageMaker](https://github.com/amazon-science/chronos-forecasting/blob/main/notebooks/deploy-chronos-to-amazon-sagemaker.ipynb) : A notebook guide on how to deploy Chronos-2 on Amazon SageMaker, facilitating easy integration and deployment of the model.
- [Chronos-2 technical report](https://arxiv.org/abs/2510.15821) : The technical report detailing the architecture, training process, and experimental results of Chronos-2.
- [Chronos GitHub Repository](https://github.com/amazon-science/chronos-forecasting) : The GitHub repository for Chronos, providing access to the source code, documentation, and additional resources for Chronos-2.

## Topics

![[topics/Model/Chronos 2]]

![[topics/Concept/In context learning ICL]]

![[topics/Model/Time Series Foundation Models TSFMs]]