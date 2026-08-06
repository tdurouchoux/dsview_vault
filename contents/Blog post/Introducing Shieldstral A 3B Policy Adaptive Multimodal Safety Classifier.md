---
already_read: true
link: https://mistral.ai/news/shieldstral/
read_priority: 0
relevance: 4
source: linkedin
tags:
- Large_Language_Model
type: Content
upload_date: '2026-08-06'
---

https://mistral.ai/news/shieldstral/

## Summary

Shieldstral is a 3B open-weights multimodal safety classifier that outperforms larger models by framing content moderation as a policy-adaptive question-answering task.

**Key Features**
- 3B parameter model matching performance of models up to 7x its size.
- Policy-adaptive: accepts plain-language policies at inference time without retraining.
- Unified interface for text, image, and text+image safety evaluation.
- Returns calibrated safety scores from a single forward pass.
- Runs efficiently on a single 16GB NVIDIA GPU.
- Released under Apache 2.0 license.

**Technical Approach**
- Frames moderation as binary question-answering (yes/no) with three inputs: *Instruct*, *Query*, *Document*.
- Trained on heterogeneous data with unified instruction–query–document format.
- Uses contrastive pairs to teach policy discrimination rather than memorization.
- Augments scarce visual safety data with general-purpose image datasets.
- Combines checkpoints via SLERP for calibration and adaptability.

**Benchmarks**
- Evaluated on text safety, refusal detection, policy adaptability, and multimodal safety.
- Outperforms open guard models up to 7x its size across all axes.

**Next Steps**
- Focus on multilingual coverage, longer-document robustness, and broader multimodal safety.

## Links

- [Shieldstral Model Documentation](https://docs.mistral.ai/models/model-cards/shieldstral-1-0) : Official documentation for Shieldstral, including model specifications, usage guidelines, and technical details about the 3B open-weights multimodal safety classifier.
- [Shieldstral Model on Hugging Face](https://huggingface.co/mistralai/Shieldstral-1.0-3B) : Hugging Face repository for Shieldstral, providing open-source access to the model weights, inference examples, and community contributions.
- [Shieldstral Technical Report (arXiv)](https://arxiv.org/abs/2607.25857) : Academic paper detailing the technical underpinnings of Shieldstral, including methodology, benchmarks, and performance comparisons with other models.
- [Mistral Forge Platform Documentation](https://mistral.ai/products/forge/) : Documentation for Mistral's Forge platform, which was used to train, align, and evaluate Shieldstral, including infrastructure and workflow details.


## Topics

![[topics/Model/Shieldstral]]

![[topics/Platform/Forge]]

![[topics/Concept/Policy adaptive safety classification]]

![[topics/Concept/AI Moderation]]

![[topics/Concept/Open Secure AI Alliance]]