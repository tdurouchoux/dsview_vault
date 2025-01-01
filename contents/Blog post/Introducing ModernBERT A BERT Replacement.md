---
already_read: true
link: https://huggingface.co/blog/modernbert?utm_campaign=Data_Elixir&utm_source=Data_Elixir_516
read_priority: 4
source: Data Elixir
tags:
- Large_Language_Model
- Natural_Language_Processing
type: Content
upload_date: '2025-01-01'
---

https://huggingface.co/blog/modernbert?utm_campaign=Data_Elixir&utm_source=Data_Elixir_516
## Summary

ModernBERT is a new family of encoder-only models that improves upon BERT with enhanced performance, efficiency, and a longer context length of 8192 tokens. It is designed as a direct replacement for BERT-like models, available in base (139M parameters) and large (395M parameters) sizes. Key features include:

- **Architecture Improvements**: ModernBERT incorporates advanced transformer techniques, such as rotary positional embeddings and GeGLU layers, optimizing the model for longer sequences and better performance.
- **Efficiency**: It utilizes Flash Attention 2, enabling faster processing and reduced memory usage, making it suitable for real-world applications on consumer-grade GPUs.
- **Training Data Diversity**: Trained on 2 trillion tokens from varied sources, including code, ModernBERT excels in programming-related tasks and long-context retrieval.
- **Performance**: It outperforms previous models like DeBERTaV3 in various benchmarks while being significantly faster and more memory-efficient.

ModernBERT is positioned to become the new standard for encoder-only models, particularly in applications like retrieval-augmented generation (RAG) and recommendation systems. It supports standard BERT fine-tuning methods and is compatible with existing frameworks for various downstream tasks.
## Links

1. [ModernBERT documentation page](https://huggingface.co/docs/transformers/main/en/model_doc/modernbert) - Official documentation for ModernBERT, detailing its architecture, usage, and features.
2. [arXiv](https://arxiv.org/abs/2412.13663) - A research paper that may provide additional insights into the methodologies and innovations behind ModernBERT.
3. [GitHub - Flash Attention](https://github.com/Dao-AILab/flash-attention) - Repository for Flash Attention, which is recommended for use with ModernBERT to enhance efficiency.
4. [Kaggle - Stack Overflow Questions Dataset](https://www.kaggle.com/datasets/imoore/60k-stack-overflow-questions-with-quality-rate) - A dataset that can be useful for fine-tuning ModernBERT on programming-related tasks.
5. [ColBERT](https://huggingface.co/colbert-ir/colbertv2.0) - A model that may be relevant for understanding retrieval tasks in conjunction with ModernBERT.
## Topics

![](topics/Model/ModernBERT)

![](topics/Library/Transformers%20and%20Switch%20Transformers)

![](topics/Tool/Flash%20Attention%202)

![](topics/Concept/Masked%20Language%20Model%20MLM)

![](topics/Dataset/StackOverflow%20QA)