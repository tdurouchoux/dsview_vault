---
already_read: false
link: https://github.com/Nixtla/nixtla/tree/main/experiments/foundation-time-series-arena
read_priority: 1
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-06-12'
---

https://github.com/Nixtla/nixtla/tree/main/experiments/foundation-time-series-arena
## Summary

The content discusses a benchmark study comparing various foundation models for time series forecasting, highlighting the performance of TimeGPT-1, which outperforms other models in accuracy and inference speed. Key findings include:

- TimeGPT-1 is the most accurate and fastest model, followed closely by TimesFM from Google.
- Chronos from Amazon ranks third but has slower inference times.
- Other models like Moirai and Lag-Llama often perform worse than classical statistical and machine learning methods.
- The study evaluates over 30,000 unique time series across different frequencies and includes comparisons with traditional forecasting methods.

The rise of zero-shot foundation models is emphasized, allowing practitioners to forecast without extensive training. The benchmark aims to provide a reproducible framework for evaluating these models, addressing challenges like data leakage and the need for transparency in model training.

Preliminary conclusions suggest that while TimeGPT-1 is currently the best-performing model, practitioners should still conduct their own evaluations before deployment. The content also mentions ongoing improvements and new features for TimeGPT-1, including enhanced long-term forecasting capabilities and better documentation.
## Links

1. [TimeGPT-1](https://arxiv.org/abs/2310.03589b) - A foundational model for time series forecasting that has shown superior accuracy and speed in benchmarks.
2. [Chronos: Learning the Language of Time Series](https://arxiv.org/abs/2402.02592) - A foundational model developed by Amazon for time series forecasting, compared in the benchmark study.
3. [TimesFM: A decoder-only foundation model for time-series forecasting](https://arxiv.org/abs/2403.07815) - Google's foundational model for time series forecasting, also evaluated in the benchmark.
4. [Announcing TimeGEN-1 in Azure AI: Leap Forward in Time Series](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/announcing-timegen-1-in-azure-ai-leap-forward-in-time-series/ba-p/4140446) - A blog post detailing the deployment of Nixtla's TimeGEN-1 model on Azure, enhancing accessibility for users.
5. [Nixtla Documentation](https://docs.nixtla.io/) - Comprehensive documentation for Nixtla's models, including setup and usage instructions for TimeGPT-1 and TimeGEN-1.
## Topics

![](topics/Model/TimeGPT%201)

![](topics/Model/TimesFM)

![](topics/Model/Chronos)

![](topics/Model/Moirai)

![](topics/Model/Lag%20Llama)