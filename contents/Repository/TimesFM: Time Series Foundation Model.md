---
already_read: false
link: https://github.com/google-research/timesfm#readme
read_priority: 1
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-05-29'
---

https://github.com/google-research/timesfm#readme
## Summary

TimesFM (Time Series Foundation Model) is a pretrained model developed by Google Research for time-series forecasting. It is designed for univariate forecasting with context lengths up to 512 time points and supports various horizon lengths. Key features include:

- **Installation**: Can be installed via pip or conda, with specific environment setups for GPU and CPU.
- **Inference**: Supports forecasting from both array inputs and pandas dataframes, requiring frequency indicators for time series.
- **Covariates Support**: Allows for static and dynamic covariates to enhance forecasting accuracy.
- **Finetuning**: Users can finetune the model on their datasets.
- **Usage**: The model can be initialized and loaded with checkpoints for forecasting tasks.

The model focuses on point forecasts and does not support probabilistic forecasts, although experimental quantile heads are available. It is recommended to have at least 16GB of RAM for optimal performance.
## Links

1. [A decoder-only foundation model for time-series forecasting](https://arxiv.org/abs/2310.10688) - Research paper detailing the foundation model for time-series forecasting.
2. [Hugging Face checkpoint repo](https://huggingface.co/google/timesfm-1.0-200m) - Repository for downloading model checkpoints for TimesFM.
3. [notebooks/finetuning.ipynb](https://github.com/google-research/timesfm/blob/master/notebooks/finetuning.ipynb) - Example of finetuning the TimesFM model on a new dataset.
4. [notebooks/covariates.ipynb](https://github.com/google-research/timesfm/blob/master/notebooks/covariates.ipynb) - Example demonstrating the use of covariates with the TimesFM model.
5. [extended benchmarks](https://github.com/google-research/timesfm/tree/master/experiments/extended_benchmarks) - Directory containing extended benchmark results for the TimesFM model.
## Topics

- [[topics/Model/TimesFM]]
- [[topics/Platform/Hugging Face]]
- [[topics/Concept/Covariates Support]]
- [[topics/Concept/Fine-tuning]]
- [[topics/Concept/Installation Methods]]