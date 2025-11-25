---
already_read: true
link: https://generalistai.com/blog/nov-04-2025-GEN-0
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-11-26'
---

https://generalistai.com/blog/nov-04-2025-GEN-0
## Summary

The content introduces GEN-0, a new class of embodied foundation models designed for multimodal training on high-fidelity raw physical interaction data. Key points include:

- **Architecture and Training**: GEN-0 builds on vision and language models, incorporating Harmonic Reasoning to enable simultaneous thinking and acting, crucial for real-world physical systems.
- **Scaling Laws**: GEN-0 exhibits strong scaling laws, where more pretraining data and compute consistently improve downstream performance. A phase transition is observed at 7B parameters, with larger models continuing to improve while smaller ones exhibit ossification.
- **Harmonic Reasoning**: This approach allows for asynchronous, continuous-time streams of sensing and acting tokens, enabling large model sizes without relying on System1-System2 architectures or inference-time guidance.
- **Cross-Embodiment**: GEN-0 architecture is designed to work on different robots, tested on 6DoF, 7DoF, and 16+DoF semi-humanoid robots.
- **Data**: GEN-0 is pretrained on over 270,000 hours of real-world manipulation data, growing at 10,000 hours per week. The data quality and diversity are emphasized over sheer volume.
- **Science of Pretraining**: Different mixtures of pretraining data yield models with varying characteristics, impacting downstream performance. Experiments show that models with low prediction errors and low reverse KL tend to perform better with supervised finetuning.

The content also highlights the infrastructure built to support this scale of robot data, including custom hardware, dataloaders, and network infrastructure. The goal is to create embodied foundation models whose capabilities predictably scale with physical interaction data, marking a new era in robotics.
## Links

- [PaLM-E: An Embodied Multimodal Language Model](https://palm-e.github.io/) : This link points to the PaLM-E model, an embodied multimodal language model that integrates various modalities, including vision and language, to enhance robotic interactions and understanding.
- [Helix: A Vision-Language-Action Model for Generalist Humanoid Control](https://www.figure.ai/news/helix) : This link points to the Helix model, a vision-language-action model designed for generalist humanoid control, which is relevant to the discussion on embodied foundation models and their applications in robotics.
- [Learning to Reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/) : This link points to a resource on learning to reason with large language models (LLMs), which is pertinent to the content discussing the reasoning capabilities of GEN-0 and its ability to think and act seamlessly.

## Topics

![[topics/Model/GEN 0]]

![[topics/Concept/Harmonic Reasoning]]

![[topics/Concept/Scaling Laws for Robotics]]

![[topics/Concept/Ossification in Robotics]]

![[topics/Concept/Cross Embodiment]]

![[topics/Dataset/In house Robotics Dataset]]