---
already_read: true
link: https://robjhyndman.com/hyndsight/foundation_models.html
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Time_Series
- Model_evaluation
type: Content
upload_date: '2026-09-26'
---

https://robjhyndman.com/hyndsight/foundation_models.html

## Summary

Time series foundation models shift forecasting workflows but have yet to prove superior accuracy over well-tuned statistical methods.

**Key claims**
- Foundation models enable single-model forecasting at scale without dataset-specific training.
- Accuracy gains over statistical baselines are often overstated due to poor benchmarking (Bergmeir, 2024).

**Evaluation pitfalls**
- Benchmarks frequently use under-tuned statistical models or leak training data (Meyer et al., 2025: 94% of 401 datasets had pre-training exposure).
- Public leaderboards may hide domain-specific variance and ignore production constraints (latency, cost, robustness).

**Operational considerations**
- Statistical models (ETS, ARIMA, Theta) remain cheap, fast, and interpretable.
- Foundation models introduce inference costs, vendor dependency, and limited explainability.
- Real-world performance hinges on handling structural breaks, exogenous variables, and missing data—rarely reported in benchmarks.

## Links

- [Foundation forecasting models - Forecasting: Principles and Practice (Pythonic Way)](http://OTexts.com/fpppy/15-foundation-models.html) : A chapter from the online forecasting textbook by Hyndman et al. (2026) discussing foundation models in time series forecasting, including their principles, applications, and limitations.
- [Rethinking evaluation in the era of time series foundation models: (un)known information leakage challenges](https://arxiv.org/abs/2510.13654v3) : A 2025 arXiv paper by Meyer et al. highlighting challenges in evaluating time series foundation models due to data leakage and proposing methodological improvements.
- [LLMs and foundational models: Not (yet) as good as hoped](https://cbergmeir.com/papers/Bergmeir2024LLMs.pdf) : A 2024 paper by Christoph Bergmeir critically assessing the performance of LLMs and foundational models in time series forecasting, emphasizing gaps between claims and empirical results.


## Topics

![[topics/Concept/Data Contamination]]

![[topics/Concept/Rolling Origin Backtesting]]

![[topics/Concept/MASE Mean Absolute Scaled Error]]

![[topics/Dataset/Time Series Datasets]]

![[topics/Concept/Foundation Models]]

![[topics/Model/Transformer]]

![[topics/Concept/Exogenous Variables]]