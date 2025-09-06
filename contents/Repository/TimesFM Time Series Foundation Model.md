---
already_read: false
link: https://github.com/google-research/timesfm
read_priority: 4
relevance: 0
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-05-29'
---

https://github.com/google-research/timesfm
## Summary

TimesFM is a pretrained time-series foundation model developed by Google Research for time-series forecasting. It offers two main checkpoints: timesfm-1.0-200m and timesfm-2.0-500m, with the latter providing improved performance and a longer context length. The model supports univariate time series forecasting with optional frequency indicators and experimental quantile heads. It can be used for point forecasts but does not support probabilistic forecasts. TimesFM also includes support for external regressors and finetuning on custom datasets. The model is available in both PAX (JAX) and PyTorch versions, with specific installation instructions provided for each. The repository includes examples and notebooks for usage, finetuning, and covariates support. TimesFM has been benchmarked and shown to perform well on leading time-series forecasting tasks.
## Links

- [Google Research Blog on TimesFM](https://research.google/blog/a-decoder-only-foundation-model-for-time-series-forecasting/) : This link points to the Google Research blog post about TimesFM, providing an overview and insights into the development and application of the TimesFM model.
- [Hugging Face Release of TimesFM](https://huggingface.co/collections/google/timesfm-release-66e4be5fdb56e960c1e482a6) : This link points to the Hugging Face release page for TimesFM, where model checkpoints and additional resources can be downloaded.
- [GIFT-Eval Benchmark](https://huggingface.co/spaces/Salesforce/GIFT-Eval) : This link points to the GIFT-Eval benchmark on Hugging Face, which includes TimesFM 2.0 and provides comprehensive time-series benchmarking results.

## Topics

![](topics/Model/TimesFM)