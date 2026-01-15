---
type: Concept
---

A latent tokenizer language model processes text as bytes and uses a lightweight local encoder to build contextual byte-level representations. It then uses a boundary predictor to decide where to place patch boundaries, pooling bytes into variable-length patches that feed into a global transformer.