---
type: Concept
---

The Masked Language Model (MLM) is a pre-training objective used in BERT. It involves randomly masking some tokens from the input and predicting the original vocabulary ID of the masked words based only on their context. This enables the representation to fuse left and right context, allowing for pre-trained deep bidirectional representations. The MLM objective is inspired by the Cloze task and helps in reducing the pre-train/fine-tune mismatch.