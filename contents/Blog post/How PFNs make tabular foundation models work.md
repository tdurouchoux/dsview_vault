---
already_read: true
link: https://mindfulmodeler.substack.com/p/how-pfns-make-tabular-foundation
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Supervised_Learning
- Data_Analysis
type: Content
upload_date: '2026-03-14'
---

https://mindfulmodeler.substack.com/p/how-pfns-make-tabular-foundation
## Summary

The content discusses the concept of Prior-Data Fitted Networks (PFNs) and their role in enabling tabular foundation models (TFMs) to work effectively. Here are the key points:

1. **Pre-training Tabular Models**: Traditional tabular models are trained from scratch, with no transfer of knowledge between different tasks. Unlike unstructured data (e.g., images), tabular data is highly variable in structure, making pre-training non-obvious.

2. **Posterior Predictive Distribution**: The goal is to predict the distribution \( p(y|x_{\text{new}}, X_{\text{train}}, y_{\text{train}}) \), which is the posterior predictive distribution in Bayesian terms. This distribution provides utility like quantile regression, uncertainty quantification, and outlier detection.

3. **Bayesian Approach**: Using Bayes' theorem, the posterior predictive distribution can be expressed in terms of a latent variable φ representing the underlying task. This allows for the integration of pre-training data from other tasks.

4. **PFNs and TabPFN**: PFNs approximate the posterior predictive distribution by defining a prior over data-generating processes. TabPFN, a specific instance of PFNs, uses a transformer architecture adapted for tabular data. This architecture processes the entire dataset in a single forward pass, enabling in-context learning.

5. **Key Components**: The approach involves:
   - A prior probability \( p(φ) \) of tasks.
   - Likelihood of the training data given the task \( p(X_{\text{train}}, y_{\text{train}}|φ) \).
   - Probability of the target given features and task \( p(y|x_{\text{new}}, φ) \).

6. **Synthetic Data and Transformers**: PFNs use synthetic data generated from structural causal models to define the prior implicitly. A transformer-based network processes the data, allowing the model to condition predictions on both samples and feature relationships.

7. **General Framework**: PFNs provide a general framework for pre-training tabular foundation models, with variations like TabPFN and TabICL differing in their priors, architectural choices, and pre- and post-processing steps.

The content concludes by hinting at a future deep dive into the architecture of TabPFN.
## Links

- [TabPFN Paper](https://arxiv.org/abs/2112.10510) : The original research paper introducing Prior-Data Fitted Networks (PFNs), which is the foundation for TabPFN and other tabular foundation models.
- [TabPFN v2 Paper](https://arxiv.org/abs/2207.01848) : The research paper introducing TabPFN v2, which is an improved version of the TabPFN model.

## Topics

![[topics/Concept/Prior Data Fitted Networks PFNs]]

![[topics/Concept/Tabular Foundation Models TFMs]]

![[topics/Concept/In context learning]]

![[topics/Concept/Posterior Predictive Distribution]]

![[topics/Concept/Structural Causal Models]]