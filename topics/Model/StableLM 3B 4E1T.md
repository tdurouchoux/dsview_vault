---
type: Model
---

StableLM-3B-4E1T is a 3 billion parameter language model pre-trained under a multi-epoch regime. It is designed to study the impact of repeated tokens on downstream performance. The model is trained on 1 trillion tokens for 4 epochs, following observations that training with up to 4 epochs of repeated data yields negligible changes to loss compared to having unique data.