---
already_read: false
link: https://magazine.sebastianraschka.com/p/understanding-reasoning-llms
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2025-02-18'
---

https://magazine.sebastianraschka.com/p/understanding-reasoning-llms
## Summary

The article discusses the development and refinement of reasoning models designed to enhance the capabilities of Large Language Models (LLMs) in handling complex tasks involving multi-step reasoning. Key points include:

1. **Definition of Reasoning Models**: Reasoning models are defined as LLMs that excel in complex, multi-step tasks, such as solving puzzles and advanced mathematical problems. Unlike standard LLMs that provide straightforward answers, reasoning models showcase intermediate reasoning steps.

2. **Four Main Approaches to Enhancing Reasoning Models**:
   - **Inference-Time Scaling**: Involves adjusting computational resources during inference to improve output, leveraging techniques like chain-of-thought prompting.
   - **Pure Reinforcement Learning (RL)**: Demonstrated by DeepSeek-R1-Zero, where reasoning skills emerged through unsupervised RL without prior supervised fine-tuning.
   - **Supervised Fine-tuning Plus RL (SFT + RL)**: Utilized in DeepSeek-R1, this method combines fine-tuning with RL, improving reasoning abilities significantly over just RL.
   - **Distillation**: Smaller models are trained using data generated from larger models, striking a balance between efficiency and capability while maintaining affordability.

3. **Strengths and Limitations**: Reasoning models excel in complex tasks but can be less efficient and more error-prone for simpler tasks. They tend to be costlier and more verbose.

4. **Practical Considerations**: Discusses the development costs and efficiency considerations—particularly how distillation offers a budget-friendly means to achieve strong reasoning performance.

5. **Future Directions**: Highlights the potential for combining SFT + RL with inference-time scaling and explores innovative training methodologies such as journey learning, which includes learning from incorrect solution paths to enhance reasoning robustness.

Overall, the article offers insights into effective strategies for developing reasoning models within the context of rapidly evolving AI, emphasizing practical implementation and cost-efficiency.
## Links

- [Scaling LLM Test-Time Compute Optimally](https://arxiv.org/abs/2408.03314) : Discusses methods for scaling LLM inference time to improve output quality.
- [Journey Learning Paper](https://arxiv.org/abs/2410.18982) : Introduces 'journey learning' as a method to enhance model training by including incorrect paths for learning.
- [DeepSeek R1 Technical Report](https://arxiv.org/abs/2501.12948) : Technical report detailing the development process and methodologies used in creating DeepSeek's reasoning models.
- [Sky-T1 Project](https://novasky-ai.github.io/posts/sky-t1/) : A project demonstrating the training of an open-weight model at a low cost, focusing on efficient model development.
- [LLM Training: RLHF and Its Alternatives](https://magazine.sebastianraschka.com/p/llm-training-rlhf-and-its-alternatives) : Explores different training methodologies for LLMs including reinforcement learning with human feedback.

## Topics

![](topics/Concept/Reasoning%20Models)

![](topics/Tool/DeepSeek)

![](topics/Concept/Inference%20time%20Scaling)

![](topics/Concept/Reinforcement%20Learning)

![](topics/Concept/Supervised%20Fine%20Tuning%20SFT)

![](topics/Concept/Model%20Distillation)