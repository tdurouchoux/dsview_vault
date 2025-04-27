---
already_read: true
link: https://huggingface.co/blog/modernbert
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2025-01-01'
---

https://huggingface.co/blog/modernbert
## Summary

ModernBERT is introduced as a state-of-the-art successor to BERT, boasting enhancements in processing speed, sequence length (up to 8192 tokens), and performance in various NLP tasks. Designed as a drop-in replacement for BERT-like models, it offers two sizes: base (149M params) and large (395M params).

Key features include:
- Utilization of Flash Attention 2 for efficiency.
- Improvements in architecture through rotary positional embeddings, GeGLU layers, and optimized normalization.
- A marked increase in training data diversity (2 trillion tokens), incorporating web documents, code, and more, leading to superior performance in programming and code retrieval tasks.

ModernBERT achieves top scores on academic benchmarks, outdoing previous leaders while remaining significantly faster, especially in long-context scenarios. It combines efficient computing through techniques such as unpadding and sequence packing to improve batch processing and reduce computational waste.

Despite these advancements, ModernBERT is primarily English-focused, with plans for a multilingual version still being discussed. Future applications for ModernBERT include improved programming assistants and integration into systems requiring encoder models for efficiency and reliability in NLP tasks.
## Links

- [ModernBERT-Base Model](https://huggingface.co/answerdotai/ModernBERT-base) : The Hugging Face page for the ModernBERT-Base model which includes documentation and usage examples.
- [ModernBERT-Large Model](https://huggingface.co/answerdotai/ModernBERT-large) : The Hugging Face page for the ModernBERT-Large model, showcasing its features and documentation.
- [GLiNER: Zero-shot Named Entity Recognition Model](https://github.com/urchade/GLiNER) : A GitHub repository for GLiNER, a model specifically designed for zero-shot Named Entity Recognition.
- [arXiv Paper on ModernBERT](https://arxiv.org/abs/2412.13663) : A research paper published on arXiv detailing the ModernBERT model's architecture and performance metrics.
- [Sentence Transformers](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) : A page on Hugging Face for Sentence Transformers that can be used for similarity and retrieval tasks.

## Topics

![](topics/Model/ModernBERT)

![](topics/Library/Hugging%20Face%20Transformers)

![](topics/Concept/Masked%20Language%20Model%20MLM)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Alternating%20Attention%20Mechanism)

![](topics/Concept/Sequence%20Packing)