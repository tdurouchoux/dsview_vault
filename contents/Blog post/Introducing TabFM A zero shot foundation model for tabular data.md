---
already_read: true
link: https://research.google/blog/introducing-tabfm-a-zero-shot-foundation-model-for-tabular-data/
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Deep_Learning
type: Content
upload_date: '2026-07-22'
---

https://research.google/blog/introducing-tabfm-a-zero-shot-foundation-model-for-tabular-data/
## Summary

TabFM is a zero-shot foundation model for tabular data classification and regression, eliminating traditional bottlenecks like manual feature engineering and hyperparameter tuning. It uses in-context learning (ICL) to process entire datasets as unified prompts, leveraging a hybrid architecture with alternating row/column attention and row compression for efficiency. Trained on hundreds of millions of synthetic datasets generated via structural causal models, TabFM outperforms tuned tree-based models (e.g., XGBoost) in benchmarks (TabArena). Two configurations are offered: a default zero-shot model and an ensemble variant with cross/SVD features. TabFM will be integrated into Google BigQuery via a simple `AI.PREDICT` SQL command. Key contributors include Weihao Kong, Abhimanyu Das, and others. Code and models are available on Hugging Face and GitHub.
## Links

- [TabFM Hugging Face Repository](https://huggingface.co/google/tabfm-1.0.0-pytorch) : This link points to the Hugging Face repository for TabFM, a zero-shot foundation model for tabular data. It likely contains the model weights, implementation details, and usage instructions for integrating TabFM into projects.
- [TabFM GitHub Repository](https://github.com/google-research/tabfm) : This link leads to the official GitHub repository for TabFM, where users can access the source code, documentation, and examples for training or fine-tuning the model on their own datasets.
- [TabArena Leaderboard](https://huggingface.co/spaces/TabArena/leaderboard) : This link directs to the TabArena leaderboard, which provides performance benchmarks and Elo scores for TabFM and other models on tabular data tasks. It is useful for comparing TabFM's performance against state-of-the-art methods.
- [Platt Scaling (Wikipedia)](https://en.wikipedia.org/wiki/Platt_scaling) : This link explains Platt scaling, a method used for calibrating the outputs of classification models like TabFM. It is relevant for understanding how TabFM-Ensemble incorporates Platt scaling for improved prediction calibration.
- [Singular Value Decomposition (Wikipedia)](https://en.wikipedia.org/wiki/Singular_value_decomposition) : This link provides an overview of Singular Value Decomposition (SVD), a technique mentioned in the context of TabFM-Ensemble for enhancing model performance. It is useful for understanding the mathematical foundation behind the feature extraction process in TabFM.

## Topics

![[topics/Model/TabFM]]

![[topics/Concept/In Context Learning ICL]]

![[topics/Concept/Structural Causal Models SCMs]]

![[topics/Library/TabPFN Tabular Prior data Fitted Networks]]

![[topics/Library/TabICL]]

![[topics/Platform/TabArena]]

![[topics/Tool/Google BigQuery]]