---
already_read: false
link: https://github.com/google-research/timesfm
read_priority: 1
relevance: 0
source: null
tags:
- Time_Series
type: Content
upload_date: '2024-05-29'
---

https://github.com/google-research/timesfm
## Summary

TimesFM (Time Series Foundation Model) is a pretrained model created by Google Research specifically for time-series forecasting. It is designed to facilitate predictions in univariate time series data, accommodating various context and horizon lengths. The current versions include:

- **TimesFM 1.0-200m**: Supports context lengths up to 512 timepoints, focusing on point forecasts.
- **TimesFM 2.0-500m**: A more advanced version with up to 2048 timepoints and improved performance metrics. This version offers longer context lengths and additional features like quantile forecasting.

Key features include:

1. **Fine-tuning Support**: Users can adjust the model to their specific datasets using PyTorch or JAX frameworks. This allows for improved prediction accuracy based on unique data attributes.
2. **Covariate Support**: The model accommodates external regressors, enabling predictions that factor in additional variables like promotions or weather conditions.
3. **Installation**: Users need specific versions of Python (3.10 for JAX and 3.11 for PyTorch) to set up the model. Guidance is provided for local installation using the Poetry package manager.
4. **Usage**: Users can utilize the model through API methods to forecast using both array and pandas DataFrame inputs, with detailed parameter configurations for context and frequency.

Benchmarking indicates that TimesFM 2.0 outperforms other models in time-series forecasting evaluations. The project encourages contributions and provides guidelines for code formatting.
## Links

- [Google Research Blog: A Decoder-Only Foundation Model for Time-Series Forecasting](https://research.google/blog/a-decoder-only-foundation-model-for-time-series-forecasting/) : An article discussing the TimesFM model and its applications for time-series forecasting.
- [Hugging Face TimesFM Release Collection](https://huggingface.co/collections/google/timesfm-release-66e4be5fdb56e960c1e482a6) : A collection of TimesFM model checkpoints and resources available on Hugging Face.
- [Finetuning Example Notebook](https://github.com/google-research/timesfm/blob/master/notebooks/finetuning.ipynb) : Jupyter notebook providing an example of how to finetune the TimesFM model on a new dataset.
- [Covariates Support Notebook](https://github.com/google-research/timesfm/blob/master/notebooks/covariates.ipynb) : Jupyter notebook demonstrating how to implement covariate support with TimesFM for better forecasting.
- [GIFT-Eval Benchmark](https://huggingface.co/spaces/Salesforce/GIFT-Eval) : A comprehensive benchmarking tool for evaluating time-series forecasting models.

## Topics

![](topics/Model/TimesFM)

![](topics/Concept/Covariate%20Support%20in%20Time%20Series%20Forecasting)

![](topics/Library/PyTorch)

![](topics/Library/JAX)

![](topics/Platform/Hugging%20Face)