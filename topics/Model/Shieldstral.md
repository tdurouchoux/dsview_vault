---
type: Model
---

A 3-billion-parameter open-weights multimodal safety classifier developed by Mistral AI. Shieldstral frames content moderation as a policy-adaptive question-answering task, allowing plain-language policies to be supplied at inference time without retraining. It evaluates both text and image content for safety, returning calibrated yes/no probabilities as continuous safety scores. The model is designed to unify tasks such as prompt classification, response moderation, refusal detection, and toxicity detection into a single framework. Shieldstral outperforms larger open guard models (up to 7x its size) across text safety, refusal detection, policy adaptability, and multimodal moderation benchmarks, and is optimized to run efficiently on a single 16GB NVIDIA GPU.