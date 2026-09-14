---
type: Model
---

TimesFM-3 is a zero-shot foundation model for multivariate time series forecasting, designed to predict multiple related time series simultaneously with high accuracy. It builds on the decoder-only transformer architecture of its predecessors, incorporating innovations like alternating attention mechanisms (causal temporal attention and full variate attention) and non-autoregressive decoding via contiguous patch masking. The model supports multiple targets, past covariates, and past-future covariates, enabling robust forecasting without task-specific fine-tuning. It is pre-trained on over 1 trillion time points and achieves state-of-the-art performance on public benchmarks.