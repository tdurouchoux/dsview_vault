---
already_read: true
link: https://huggingface.co/blog/moe
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2024-11-18'
---

https://huggingface.co/blog/moe
## Summary

MoE (Mixture of Experts) models enhance transformer architectures by incorporating sparse layers of "experts" which enables more efficient pretraining and faster inference. Each MoE layer consists of numerous experts (neural networks) and a gating network that routes input tokens to the selected experts. While MoEs scale well and improve performance, they also pose challenges in fine-tuning due to tendencies toward overfitting and require substantial VRAM for inference.

Key highlights include:

- MoEs can achieve better performance with fewer computations compared to dense models by utilizing conditional computation.
- Historical development traces back to early 1990s research, with significant advancements over the last decade focusing on dynamic activation of model components.
- Sparsity reduces compute usage by only activating parts of the model for specific inputs, but introduces complexities in load balancing and increases the risk of certain experts being over-represented.
- Recent implementations like Switch Transformers optimize MoE architectures to enhance training stability and reduce inter-device communication costs.
- Fine-tuning requires nuanced strategies, as sparse models tend to overfit and need higher regularization. However, instruction tuning demonstrates significant benefits for MoEs.
- When deciding between MoEs and dense models, consider the throughput requirements and available computational resources: MoEs excel in high-throughput scenarios with adequate VRAM, while dense models are more suited for low-throughput settings.

Emerging directions include optimizing serving techniques, exploring extreme quantization, and research on distilling sparse MoEs to dense equivalents for reduced parameter counts.
## Links

- [Switch Transformers Paper](https://arxiv.org/abs/2101.03961) : The paper outlines the development of Switch Transformers, focusing on the ideas around mixture of experts and their scalable training techniques.
- [Megablocks Project](https://github.com/stanford-futuredata/megablocks) : An open-source project that provides efficient sparse training with mixture of experts, addressing the dynamic nature of MoEs.
- [Fairseq: Mixture of Experts LM](https://github.com/facebookresearch/fairseq/tree/main/examples/moe_lm) : This is a repository containing examples of using mixture of experts in the Fairseq framework.
- [NLLB MoE Model](https://huggingface.co/facebook/nllb-moe-54b) : A variant of the NLLB translation model that utilizes mixture of experts for improved performance.
- [Mixtral 8x7B Model](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1) : A high-quality mixture of experts model that significantly outperforms other models in terms of efficiency and inference speed.

## Topics

![](topics/Concept/Mixture%20of%20Experts%20MoE)

![](topics/Concept/Sparsity%20in%20Neural%20Networks)

![](topics/Concept/Switch%20Transformers)

![](topics/Concept/Router%20Z%20loss)

![](topics/Concept/Load%20Balancing%20in%20MoEs)

![](topics/Platform/Hugging%20Face)

![](topics/Library/Fairseq)

![](topics/Library/Megablocks)

![](topics/Dataset/Mixtral%208x7B)