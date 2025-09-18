---
already_read: true
link: https://huggingface.co/blog/modernbert
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Natural_Language_Processing
type: Content
upload_date: '2025-01-01'
---

https://huggingface.co/blog/modernbert
## Summary

ModernBERT is a new state-of-the-art encoder-only model that improves upon BERT and its successors in terms of speed, accuracy, and context length. It is available in two sizes: base (149M parameters) and large (395M parameters), and can be used as a direct replacement for BERT-like models. ModernBERT supports a sequence length of 8,192 tokens, which is significantly longer than most existing encoders, and includes a large amount of code in its training data, making it unique for code retrieval tasks.

The model is designed to be efficient and practical, with a focus on real-world applications rather than just benchmarks. It uses a modernized transformer architecture, with improvements such as rotary positional embeddings, GeGLU layers, and an extra normalization layer. ModernBERT also employs several efficiency techniques, including alternating attention, unpadding and sequence packing, and hardware-aware model design.

ModernBERT is trained on a diverse range of English sources, including web documents, code, and scientific articles, with a total of 2 trillion tokens. The training process involves three phases, with the final phase using a trapezoidal learning rate. The model is designed to be good across the board, with competitive performance on both long-context and short-context tasks.

ModernBERT is expected to become the new standard for encoder-only models in various applications, such as RAG pipelines and recommendation systems. It is available on the Hugging Face Hub and will be included in v4.48.0 of the Transformers library. The creators of ModernBERT are also opening a call for demos, with prizes for the best ones.
## Links

- [ModernBERT-Base Model](https://huggingface.co/answerdotai/ModernBERT-base) : The Hugging Face page for the ModernBERT-Base model, providing access to the model's details, usage instructions, and performance metrics.
- [ModernBERT-Large Model](https://huggingface.co/answerdotai/ModernBERT-large) : The Hugging Face page for the ModernBERT-Large model, offering comprehensive information on the larger version of ModernBERT, including its architecture and capabilities.
- [ModernBERT Documentation](https://huggingface.co/docs/transformers/main/en/model_doc/modernbert) : Official documentation for ModernBERT on Hugging Face, detailing how to use the model with the Transformers library, including code examples and configuration details.

## Topics

![[topics/Concept/Rotary Positional Embeddings RoPE)]]

![[topics/Concept/Unpadding and Sequence Packing)]]

![[topics/Concept/GeGLU Layers)]]

![[topics/Model/ModernBERT)]]

![[topics/Concept/Hardware Aware Model Design)]]

![[topics/Concept/Alternating Attention)]]