---
already_read: true
link: https://huggingface.co/blog/not-lain/kv-caching
read_priority: 0
relevance: 3
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-09-13'
---

https://huggingface.co/blog/not-lain/kv-caching

## Summary

KV caching is a technique that speeds up transformer inference by reusing past attention computations, significantly improving efficiency for text generation.

**Core Idea**
- KV caching stores keys (K) and values (V) from previous tokens to avoid recomputing attention for the entire sequence at each step.

**Mechanism**
- First token: computes and caches [K₁, V₁].
- Subsequent tokens: appends new [Kₙ, Vₙ] to the cache and reuses the full history for attention.
- Attention is computed using cached K/V and the new query (Q).

**Comparison: KV Caching vs. Standard Inference**
- **Computation per word**: standard repeats all calculations; KV caching reuses past K/V.
- **Memory**: standard uses less per step but grows with sequence length; KV caching uses extra memory for the cache.
- **Speed**: standard slows with longer texts; KV caching maintains speed by avoiding redundant work.
- **Efficiency**: standard has high computational cost; KV caching is faster and more efficient.
- **Long texts**: standard struggles; KV caching excels by remembering past steps.

**Performance**
- Benchmark on T4 GPU: KV caching achieved ~5.21x speedup (11.7s vs. 1min 1s).

**Implementation**
- Enabled by default in Hugging Face Transformers via `use_cache=True`.
- Custom PyTorch implementation involves updating and concatenating cached K/V tensors.
- Applied per transformer block (each has its own attention heads).

## Links

- [Transformers Key-Value Caching Explained - Hugging Face Documentation](https://huggingface.co/docs/transformers/main/en/generation_strategies#kv-caching) : Official Hugging Face documentation explaining KV caching in detail, including its implementation and usage in the `transformers` library. This is directly relevant to the blog post's technical content.
- [Mastering LLM Techniques: Inference Optimization - NVIDIA Developer Blog](https://developer.nvidia.com/blog/mastering-llm-techniques-inference-optimization/) : A detailed guide by NVIDIA on inference optimization techniques for large language models, including KV caching. This complements the blog post by providing broader context on optimization strategies.
- [KV Caching Explained - Medium Article by João Lages](https://medium.com/@joaolages/kv-caching-explained-276520203249) : A technical article explaining KV caching with a focus on practical implementation and performance benefits. This aligns well with the blog post's explanation and adds external validation.
- [Transformers Key-Value Caching - Neptune.ai Blog](https://neptune.ai/blog/transformers-key-value-caching) : A blog post by Neptune.ai that dives into the mechanics of KV caching, its benefits, and trade-offs. This provides additional insights and is highly relevant to the topic.
- [GenerationConfig.cache_implementation - Hugging Face Documentation](https://huggingface.co/docs/transformers/main_classes/text_generation#transformers.GenerationConfig.cache_implementation) : Hugging Face documentation on the `cache_implementation` parameter, which is directly related to KV caching in the `transformers` library. This is a key technical reference for implementation.


## Topics

![[topics/Concept/KV Caching]]

![[topics/Model/SmolLM2]]

![[topics/Library/PyTorch]]

![[topics/Library/Transformers]]