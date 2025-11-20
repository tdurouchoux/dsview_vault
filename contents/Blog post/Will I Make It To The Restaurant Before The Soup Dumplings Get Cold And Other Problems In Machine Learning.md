---
already_read: true
link: https://www.distributedthoughts.org/will-i-make-it-to-the-restaurant-before-the-soup-dumplings-get-cold-and-other-problems-in-machine-learning/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-11-20'
---

https://www.distributedthoughts.org/will-i-make-it-to-the-restaurant-before-the-soup-dumplings-get-cold-and-other-problems-in-machine-learning/
## Summary

The content discusses the issue of nondeterminism in machine learning, particularly in large language models (LLMs), and presents a solution developed by Thinking Machines Lab. The main points are:

1. **Nondeterminism Problem**: Even with a known route (trained model), machine learning algorithms can produce different results due to variations in batch sizes and operation grouping, leading to different rounding patterns and final outputs.

2. **Root Cause**: The nondeterminism is not due to randomness but systematic differences in how operations are grouped and ordered based on batch configuration. This affects three main operations: RMSNorm, matrix multiplication, and attention mechanisms.

3. **Solution**: Thinking Machines Lab introduced batch-invariant kernels that ensure consistent operation ordering regardless of batch size. This makes the inference process deterministic, providing the same output for the same input every time.

4. **Impact**: Deterministic inference enables precise A/B testing, easier debugging, perfect caching, and more reliable model testing. It also allows for true on-policy reinforcement learning, improving the stability and reliability of training methods like RLHF and DPO.

5. **Implementation**: The solution involves rethinking how fundamental GPU operations work to ensure consistent reduction order and tile sizes. The team contributed changes to PyTorch's FlexAttention to support this.

6. **Broader Implications**: The solution is freely available, encouraging widespread adoption and improving the reliability of LLM inference. It addresses a fundamental problem in machine learning, making experiments more reproducible and research more efficient.

7. **Future Outlook**: The authors expect batch-invariant kernels to become standard in major inference engines and cloud providers' serving infrastructure, similar to how HTTPS and Unicode support became ubiquitous.

The content emphasizes the importance of solving foundational problems in infrastructure to enable systematic progress in machine learning.
## Links

- [Defeating Nondeterminism in LLM Inference](https://arxiv.org/abs/2310.16834?ref=distributedthoughts.org) : The full paper on defeating nondeterminism in LLM inference, including technical details, benchmarks, and ablation studies.
- [Batch-Invariant Ops on GitHub](https://github.com/thinking-machines-lab/batch-invariant-ops?ref=distributedthoughts.org) : The GitHub repository for batch-invariant kernel implementations, related to the paper on defeating nondeterminism in LLM inference.

## Topics

![[topics/Concept/Nondeterminism in Machine Learning]]

![[topics/Concept/Batch Invariant Kernels]]

![[topics/Concept/On Policy vs Off Policy Reinforcement Learning]]

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF]]

![[topics/Concept/FlexAttention]]