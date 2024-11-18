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

TimesFM (Time Series Foundation Model) is a pretrained model developed by Google Research for time-series forecasting. It is designed to handle univariate time series with context lengths up to 512 time points and supports various forecasting horizons. Key features include:

- **Installation**: Available via pip for both PyTorch and PAX versions, with specific Python version requirements.
- **Inference**: Supports forecasting from array inputs or pandas DataFrames, requiring frequency indicators categorized as high, medium, or low.
- **Covariates Support**: Allows integration of static and dynamic covariates to enhance forecasting accuracy.
- **Finetuning**: Users can finetune the model on custom datasets.
- **Benchmarks**: Performance benchmarks are provided for evaluation.

The model is not officially supported by Google and requires at least 16GB of RAM for optimal performance.
## Links

1. [Hugging Face TimesFM Checkpoint](https://huggingface.co/google/timesfm-1.0-200m) - Repository for downloading the TimesFM model checkpoints for inference.
2. [A Decoder-Only Foundation Model for Time-Series Forecasting](https://research.google/blog/a-decoder-only-foundation-model-for-time-series-forecasting/) - Blog post detailing the development and capabilities of the TimesFM model.
3. [Finetuning Example Notebook](https://github.com/google-research/timesfm/blob/master/notebooks/finetuning.ipynb) - Jupyter notebook demonstrating how to finetune the TimesFM model on a new dataset.
4. [Covariates Support Notebook](https://github.com/google-research/timesfm/blob/master/notebooks/covariates.ipynb) - Jupyter notebook providing examples of using static and dynamic covariates with the TimesFM model.
5. [Extended Benchmarks](https://github.com/google-research/timesfm/tree/master/experiments/extended_benchmarks) - Directory containing benchmarks for evaluating the performance of the TimesFM model.
## Topics

![](topics/Model/TimesFM)

![](topics/Platform/Hugging%20Face)

![](topics/Concept/Covariates%20Support)

![](topics/Product/PyTorch)

![](topics/Product/Poetry)