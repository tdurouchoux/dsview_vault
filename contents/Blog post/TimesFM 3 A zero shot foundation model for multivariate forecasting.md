---
already_read: false
link: https://research.google/blog/timesfm-3-a-zero-shot-foundation-model-for-multivariate-forecasting/
read_priority: 4
relevance: 0
source: Alpha Signal
tags:
- Time_Series
- Deep_Learning
type: Content
upload_date: '2026-09-14'
---

https://research.google/blog/timesfm-3-a-zero-shot-foundation-model-for-multivariate-forecasting/

## Summary

TimesFM-3 is a zero-shot foundation model for multivariate time series forecasting that outperforms existing models on major benchmarks.

**Key Features**
- 330M parameters, pre-trained on >1T time points (real-world + synthetic).
- Zero-shot generalization: no task-specific fine-tuning required.
- Native support for multivariate forecasting: multiple targets, past covariates, and past-future (dynamic) covariates.

**Architecture**
- Decoder-only transformer with contiguous patching (32 time steps per patch).
- Alternating attention: causal temporal (horizontal) + full variate (vertical) across series.
- Non-autoregressive decode: single-pass forecasting via Contiguous Patch Masking.
- Predicts 9 quantiles (10th–90th percentile) per target for probabilistic forecasts.

**Performance**
- Top-ranked on Gift-Eval, FEV-Bench, and Time benchmarks (point + probabilistic metrics).
- Outperforms Chronos-2, Toto 2.0, and TimesFM-2.5 in both univariate and multivariate modes.
- Multivariate mode leverages cross-series info/covariates for further accuracy gains.

**Availability**
- Open-sourced on GitHub and Hugging Face.
- BigQuery integration (AI.FORECAST) coming soon.

## Links

- [TimesFM-3 on Hugging Face](https://huggingface.co/google/timesfm-3.0-pytorch) : Official Hugging Face repository for TimesFM-3, providing access to the pre-trained model weights, inference code, and usage examples for multivariate time series forecasting.
- [TimesFM GitHub Repository](https://github.com/google-research/timesfm) : GitHub repository for the TimesFM family of models, including TimesFM-3, with code, documentation, and examples for implementation and fine-tuning.
- [TimesFM-2.5 on Hugging Face](https://huggingface.co/google/timesfm-2.5-200m-pytorch) : Hugging Face repository for TimesFM-2.5, the predecessor of TimesFM-3, offering a univariate forecasting model for comparison and legacy support.
- [TIME Leaderboard on Hugging Face](https://huggingface.co/spaces/Real-TSF/TIME-leaderboard) : Leaderboard and benchmarking space for time series forecasting models, including comparative evaluations of TimesFM-3 against other state-of-the-art models.
- [GIFT-Eval Leaderboard on Hugging Face](https://huggingface.co/spaces/Salesforce/GIFT-Eval) : Leaderboard and evaluation framework for time series forecasting models, featuring the GIFT-Eval benchmark used to assess TimesFM-3's performance.


## Topics

![[topics/Model/TimesFM 3]]

![[topics/Model/Time Series Foundation Models TSFMs]]

![[topics/Dataset/Gift Eval]]

![[topics/Dataset/FEV Bench]]

![[topics/Dataset/Time]]

![[topics/Tool/Google BigQuery]]

![[topics/Concept/Multivariate forecasting]]

![[topics/Concept/Zero shot forecasting]]

![[topics/Tool/GitHub]]

![[topics/Platform/Hugging Face]]