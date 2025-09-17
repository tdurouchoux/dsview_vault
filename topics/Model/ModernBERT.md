---
type: Model
---

ModernBERT is a family of state-of-the-art encoder-only models that represent improvements over older generation encoders. It offers an 8192 sequence length, better downstream performance, and much faster processing. ModernBERT is available as a slot-in replacement for any BERT-like models, with both a base (149M params) and large (395M params) model size. It is designed to be efficient, handling inputs up to 8,192 tokens, and is optimized for tasks such as retrieval, classification, and entity extraction. ModernBERT incorporates modern advancements in transformer architecture, including rotary positional embeddings, GeGLU layers, and hardware-aware design, making it faster and more accurate than previous models like BERT and DeBERTaV3.