---
already_read: false
link: https://thinkingmachines.ai/blog/defeating-nondeterminism-in-llm-inference/
read_priority: 5
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
- Development_tool
type: Content
upload_date: '2025-09-21'
---

https://thinkingmachines.ai/blog/defeating-nondeterminism-in-llm-inference/
## Summary

The blog post discusses the challenges of achieving deterministic results in large language model (LLM) inference, even when using greedy sampling (temperature=0). The common hypothesis that floating-point non-associativity and concurrent execution cause nondeterminism is only partially correct. The true culprit is the lack of batch invariance in LLM inference engines, which makes results depend on the batch size and other concurrent user requests.

The post explains that while individual kernels in LLMs are deterministic, the overall inference system is not due to batch invariance issues. To achieve deterministic inference, the authors propose making kernels batch-invariant, which involves ensuring that the reduction order for each element is fixed regardless of the batch size. They provide examples of how to achieve batch invariance for RMSNorm, matrix multiplication, and attention operations.

The authors also present experiments demonstrating the nondeterminism in LLM completions and the performance impact of their batch-invariant kernels. They conclude by emphasizing the importance of understanding and addressing nondeterminism in machine learning systems and encourage further research in this area.

Key takeaways:
- LLM inference is nondeterministic due to lack of batch invariance, not just floating-point non-associativity and concurrency.
- Achieving deterministic inference requires making kernels batch-invariant.
- Batch-invariant kernels can be designed for RMSNorm, matrix multiplication, and attention operations.
- Deterministic inference enables true on-policy RL and improves the reliability of LLM applications.
## Links

- [arXiv Preprint on Floating-Point Non-Associativity](https://arxiv.org/abs/2502.17387) : A preprint discussing the impact of floating-point non-associativity on attention scores and logits in transformer architectures, highlighting how parallel operations can lead to different results based on execution order.
- [OpenAI Community Discussion on Determinism](https://community.openai.com/t/a-question-on-determinism/8185/2) : A discussion on the OpenAI community forum about the determinism of LLM inference, exploring why even setting the temperature to 0 does not guarantee deterministic results.

## Topics

![[topics/Concept/Nondeterminism in Machine Learning]]

![[topics/Concept/Floating point non associativity]]

![[topics/Concept/Batch Invariance]]

![[topics/Concept/FlexAttention]]

![[topics/Concept/RLVR]]