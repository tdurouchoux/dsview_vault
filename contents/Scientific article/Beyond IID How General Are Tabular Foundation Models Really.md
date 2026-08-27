---
already_read: false
link: https://arxiv.org/pdf/2606.30410
read_priority: 5
relevance: 0
source: alphaxiv
tags:
- Deep_Learning
type: Content
upload_date: '2026-08-27'
---

https://arxiv.org/pdf/2606.30410

## Summary

This paper evaluates the generalization of tabular foundation models (TFMs) beyond standard IID settings, introducing a unified benchmark (BeyondArena) and framework (DataFoundry) to assess performance across diverse, real-world datasets.

**Motivation & Gap**
- TFMs are increasingly applied across domains but are typically evaluated only on IID benchmarks, limiting understanding of real-world generalization.
- Existing non-IID benchmarks are fragmented, lacking standardized protocols for fair, comprehensive comparisons.

**Contributions**
- **BeyondArena**: Unified benchmark with 142 curated datasets spanning IID, temporal, grouped tasks, varied scales (tiny to large), and challenging features (high-cardinality, text).
- **DataFoundry**: Python framework + metadata schema for reproducible, high-quality tabular dataset curation (checks, splits, feature encoding).
- Systematic evaluation of 3 open-source TFMs (TabDPT, TabPFN-2.6, TabICLv2) vs. 8 traditional ML baselines (e.g., XGBoost, CatBoost, RealMLP) in in-context learning (no fine-tuning).

**Methodology**
- **Dataset Curation**: 1128 candidates → 142 selected via strict criteria (uniqueness, scale, task type, real-world relevance, ethics).
- **Preprocessing**: Standardized handling of missing values, dates (10 numerical features), text (32D Qwen3 embeddings), and grouped data (50D encodings).
- **Evaluation Protocol**:
  - Outer splits: Fixed for large datasets, repeated k-fold CV for smaller ones, temporal/grouped splits for non-IID.
  - Inner splits: 8-fold CV (or 5x5-fold for tiny data) for hyperparameter tuning (25 random configs, 4h time limit).
  - Metrics: ROC AUC (binary), log-loss (multiclass), RMSE (regression); aggregated via Elo ratings and Improvability.

**Key Results**
- **Overall**: Default TFMs (TabICLv2: 1205 Elo; TabPFN-2.6: 1224 Elo) are competitive but lag behind tuned/ensembled traditional models (RealMLP T+E: 1282 Elo).
- **Strengths of TFMs**: Excel on tiny/small/IID datasets (peak performance on ~70% of datasets).
- **Weaknesses of TFMs**: Struggle on non-IID (temporal/grouped), large (>100k samples), high-dimensional (>100 features), or high-cardinality categorical data.
- **Traditional Models**: RealMLP (T+E) dominates temporal/grouped/large/high-dimensional/text datasets; CatBoost (T+E) leads on high-cardinality categorical data.
- **Correlations**: GBDTs gain advantage with larger datasets, more high-cardinality categories, or higher max cardinality.

**Ablations & Insights**
- **Splits**: Non-IID outer/inner splits are critical; IID splits for non-IID data distort rankings.
- **Preprocessing**: Grouped encoding helps most models but hurts TabPFN-2.6; Qwen3 embeddings outperform TF-IDF for short text.
- **Calibration**: Probability calibration improves log-loss for tree-based models but can degrade TFM performance.
- **Speed**: BeyondArena-Core (fewer splits) achieves 5x speedup with <10% rank instability.

**Impact & Limitations**
- **Impact**: Unified benchmarking standards, guidance for practitioners (TFMs for IID/small data; traditional models for non-IID/large/complex data), and roadmap for TFM improvement.
- **Limitations**: Limited HPO budget (25 configs), no TFM fine-tuning, only 3 TFMs evaluated, uneven sub-benchmark sizes.

## Links



## Topics

![[topics/Platform/Google Cloud]]

![[topics/Model/TabFM]]

![[topics/Library/TabPFN Tabular Prior data Fitted Networks]]

![[topics/Library/skrub]]

![[topics/Model/CatBoost]]

![[topics/Model/LightGBM]]

![[topics/Model/XGBoost]]

![[topics/Model/RealMLP]]

![[topics/Model/TabM]]