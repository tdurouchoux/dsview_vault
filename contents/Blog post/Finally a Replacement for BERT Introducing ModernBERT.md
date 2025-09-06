---
already_read: true
link: https://huggingface.co/blog/modernbert
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2025-01-01'
---

https://huggingface.co/blog/modernbert
## Summary

ModernBERT is a new family of encoder-only models that improves upon BERT with better performance, efficiency, and a longer context length of 8,192 tokens. It is available in base (149M params) and large (395M params) sizes and can be used as a direct replacement for BERT-like models. ModernBERT is designed to be efficient and practical, with optimizations for real-world applications, and it supports tasks like retrieval, classification, and code understanding. It is trained on a diverse dataset, including code and scientific articles, and uses modern techniques like rotary positional embeddings, GeGLU layers, and Flash Attention 2 for improved performance. ModernBERT is expected to become the new standard for encoder-only models in various applications, such as RAG pipelines and recommendation systems. It is available for use with the Hugging Face Transformers library and will be included in v4.48.0.
## Links

- [ModernBERT Documentation](https://huggingface.co/docs/transformers/main/en/model_doc/modernbert) : Official documentation for ModernBERT, providing detailed information on how to use the model with the Transformers library.
- [ModernBERT Base Model](https://huggingface.co/answerdotai/ModernBERT-base) : Hugging Face repository for the ModernBERT-base model, including model card, usage examples, and related resources.
- [ModernBERT Large Model](https://huggingface.co/answerdotai/ModernBERT-large) : Hugging Face repository for the ModernBERT-large model, including model card, usage examples, and related resources.

## Topics

![](topics/Model/ModernBERT)

![](topics/Concept/Alternating%20Attention)

![](topics/Concept/Unpadding%20and%20Sequence%20Packing)

![](topics/Concept/Hardware%20Aware%20Model%20Design)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)