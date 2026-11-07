---
type: Model
---

DeepSeek-V3 is a large language model with 671 billion parameters, notable for its high performance and cost-effective training. It is a strong Mixture-of-Experts (MoE) language model utilizing Multi-head Latent Attention (MLA) and DeepSeekMoE architectures, with an auxiliary-loss-free strategy for load balancing. The model is pre-trained on 14.8 trillion tokens and undergoes Supervised Fine-Tuning and Reinforcement Learning stages. It requires only 2.788M H800 GPU hours for full training and is designed for efficient inference. AirLLM enables running DeepSeek-V3 on a single GPU with ~12GB VRAM via model compression techniques like FP8 and block-wise quantization.