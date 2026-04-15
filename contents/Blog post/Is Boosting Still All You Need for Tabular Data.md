---
already_read: true
link: https://m-clark.github.io/posts/2026-03-01-dl-for-tabular-foundational/
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Deep_Learning
type: Content
upload_date: '2026-04-15'
---

https://m-clark.github.io/posts/2026-03-01-dl-for-tabular-foundational/
## Summary

Key takeaways:
- **Boosting (XGBoost, LightGBM, CatBoost) remains the pragmatic baseline** for most tabular tasks due to speed, scalability, and ease of use, but **modern deep learning (DL) models (e.g., TabPFN-v2.5, RealMLP, TabICL-v2) now often outperform boosting** on standardized benchmarks like TabArena.
- **New benchmarks (TabArena, TALENT)** and tools (pytabkit, AutoGluon) improve evaluation rigor and accessibility, making DL experimentation easier.
- **DL excels in small/medium datasets (<100k rows) or when performance is critical**, but **boosting still dominates for large datasets (>1M rows)** due to scalability and inference efficiency.
- **Foundation models** (pre-trained on synthetic/real tabular data) show promise but are limited by compute costs and dataset size constraints.
- **Practical guidance**: Start with boosting; experiment with DL if resources permit, but weigh performance gains against training time and complexity. Data nuances (size, target type, feature characteristics) heavily influence model choice.
## Links

- [TabArena Leaderboard](https://huggingface.co/spaces/TabArena/leaderboard) : A public leaderboard for evaluating and comparing state-of-the-art models on tabular data tasks, providing standardized datasets, consistent evaluation metrics, and transparency in preprocessing and hyperparameter choices.
- [pytabkit GitHub Repository](https://github.com/dholzmueller/pytabkit) : A GitHub repository providing implementations of state-of-the-art tabular deep learning models with optimized hyperparameters, a unified API, and automated preprocessing for heterogeneous data.
- [TabArena Paper (arXiv)](https://arxiv.org/abs/2506.16791) : A research paper introducing TabArena, a living benchmark for machine learning on tabular data, which sets new standards for evaluating tabular deep learning models.
- [Better by Default: Strong Pre-Tuned MLPs and Boosted Trees on Tabular Data (arXiv)](https://arxiv.org/abs/2407.04491) : A research paper discussing pre-tuned machine learning models (MLPs) and boosted trees for tabular data, highlighting their strong performance and practicality.
- [TabICLv2 Paper (arXiv)](https://arxiv.org/abs/2602.11139) : A research paper introducing TabICLv2, a scalable and open tabular foundation model that leverages in-context learning for improved performance on tabular data tasks.

## Topics

![[topics/Library/pytabkit]]

![[topics/Platform/TabArena]]

![[topics/Concept/Tabular Foundation Models TFMs]]

![[topics/Model/RealMLP]]

![[topics/Model/TabPFN Prior Data Fitted Networks]]

![[topics/Concept/Elo Rating System for Model Evaluation]]

![[topics/Concept/Diminishing Returns and Improvability in Model Scaling]]

![[topics/Library/AutoGluon]]