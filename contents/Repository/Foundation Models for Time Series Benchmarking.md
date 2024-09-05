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

The content discusses a benchmark study comparing various foundation models for time series forecasting, focusing on their accuracy and inference speed. Key findings include:

- **Top Models**: TimeGPT-1 is the most accurate and fastest model, followed closely by TimesFM from Google. Chronos from Amazon ranks third but has slower inference times. Moirai and Lag-Llama perform poorly compared to classical methods.
- **Zero-shot Models**: The rise of zero-shot foundational models allows practitioners to forecast without training their own models, simplifying the process and potentially increasing accuracy.
- **Evaluation Framework**: The study utilized over 30,000 unique time series from various datasets, comparing foundation models against traditional statistical, machine learning, and deep learning models.
- **Challenges**: Issues included creating a framework for comparison and ensuring data used was unseen by the models during training to avoid overfitting.
- **Preliminary Conclusions**: While TimeGPT-1 is highlighted as the best-performing model, practitioners are encouraged to test models on their datasets before deployment.
- **Future Work**: Plans include expanding the benchmark to include more models, probabilistic benchmarks, and fine-tuning capabilities.

The content emphasizes the importance of reproducibility and transparency in model evaluation, and it acknowledges contributions from various researchers in the field.
## Links

1. [TimeGPT-1](https://arxiv.org/abs/2310.03589b) - A foundational model for time series forecasting that has shown superior accuracy and speed.
2. [Chronos: Learning the Language of Time Series](https://arxiv.org/abs/2403.07815) - A model developed by Amazon that focuses on time series forecasting.
3. [A decoder-only foundation model for time-series forecasting](https://arxiv.org/pdf/2310.10688) - Discusses TimesFM, a model from Google that competes in the time series forecasting space.
4. [Unified Training of Universal Time Series Forecasting Transformers](https://arxiv.org/abs/2402.02592) - Details the Moirai model, which aims to unify training for time series forecasting.
5. [Lag-Llama: Towards Foundation Models for Probabilistic Time Series Forecasting](https://arxiv.org/pdf/2310.08278) - Explores the Lag-Llama model, which is designed for probabilistic forecasting in time series.
## Topics

- [[topics/Model/TimeGPT-1]]
- [[topics/Model/TimesFM]]
- [[topics/Model/Chronos]]
- [[topics/Model/Moirai]]
- [[topics/Model/Lag-Llama]]