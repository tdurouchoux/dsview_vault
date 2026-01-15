---
already_read: false
link: https://allenai.org/blog/bolmo
read_priority: 4
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
- Natural_Language_Processing
type: Content
upload_date: '2026-01-15'
---

https://allenai.org/blog/bolmo
## Summary

Bolmo is a new family of byte-level language models introduced by Ai2, designed to overcome the limitations of subword tokenization. Unlike traditional byte-level models that require expensive training from scratch, Bolmo reuses the Olmo 3 subword models' backbone and capabilities, retrofitting them into a byte-level architecture with additional training. This approach results in models that are competitive with, and sometimes surpass, state-of-the-art subword models across various tasks, including character-focused benchmarks.

Key aspects of Bolmo include:

1. **Architecture**: Bolmo processes text as bytes using a latent tokenizer language model architecture. It involves three stages: embedding bytes, using a lightweight local encoder to build contextual byte-level representations, and a boundary predictor to pool bytes into variable-length patches for the global transformer.

2. **Training**: Bolmo is trained in two stages. First, it freezes the Olmo 3 transformer and trains only the local components. In the second stage, the entire model is unfrozen and trained further to exploit byte-level information.

3. **Performance**: Bolmo 7B performs close to the original subword Olmo 3 7B across a broad evaluation suite and significantly outperforms it on character-focused benchmarks. It also outperforms other byte-level models of comparable size in most tasks.

4. **Inference Speed**: Bolmo achieves competitive decoding speeds and offers flexible compression, allowing for a smoother trade-off between speed and fidelity.

5. **Post-Training**: Byteifying allows Bolmo to inherit capabilities from post-trained subword models via weight merging, enabling zero-cost upgrades.

6. **Future Directions**: Ai2 plans to explore richer lookahead and boundary predictors, scaling byteifying to larger models, and using Bolmo for multilingual and domain-specialized systems.

Bolmo's checkpoints, code, and full paper are available for community use and further development.
## Links

- [Bolmo 7B Hugging Face](https://huggingface.co/allenai/Bolmo-7B) : Hugging Face repository for Bolmo 7B, a byte-level language model.
- [Bolmo 1B Hugging Face](https://huggingface.co/allenai/Bolmo-1B) : Hugging Face repository for Bolmo 1B, a smaller byte-level language model.
- [Bolmo Core GitHub](https://github.com/allenai/bolmo-core) : GitHub repository for Bolmo Core, the core implementation of Bolmo.

## Topics

![[topics/Model/Bolmo]]

![[topics/Model/Olmo 3]]

![[topics/Concept/Byte level Models]]

![[topics/Concept/Subword Tokenization]]

![[topics/Concept/Latent Tokenizer Language Model]]

![[topics/Concept/Byteifying]]

![[topics/Concept/Task Arithmetic]]

![[topics/Concept/Dynamic Hierarchical Setup]]