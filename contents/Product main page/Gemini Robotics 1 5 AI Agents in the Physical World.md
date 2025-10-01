---
already_read: true
link: https://deepmind.google/discover/blog/gemini-robotics-15-brings-ai-agents-into-the-physical-world/
read_priority: 0
relevance: 5
source: The Batch
tags:
- AI_agent
type: Content
upload_date: '2025-10-01'
---

https://deepmind.google/discover/blog/gemini-robotics-15-brings-ai-agents-into-the-physical-world/
## Summary

Gemini Robotics 1.5 introduces advanced AI models designed to enable robots to perform complex, multi-step tasks in the physical world. The system comprises two key models:

1. **Gemini Robotics 1.5**: A vision-language-action (VLA) model that translates visual information and instructions into motor commands, allowing robots to think before acting and explain their processes. It can learn across different robot embodiments, accelerating skill acquisition.

2. **Gemini Robotics-ER 1.5**: A vision-language model that reasons about the physical world, creates detailed plans, and calls digital tools to complete missions. It excels in spatial understanding and planning, achieving state-of-the-art performance on relevant benchmarks.

These models work together in an agentic framework, with Gemini Robotics-ER 1.5 orchestrating tasks and Gemini Robotics 1.5 executing actions. They are built on the core Gemini family of models and fine-tuned for their specific roles. The system is designed to handle complex tasks, such as sorting objects based on local guidelines, by breaking them down into simpler steps and generalizing to new tasks and environments.

Safety is a key focus, with the models implementing high-level semantic reasoning and adhering to safety policies. Google DeepMind has also released an upgraded ASIMOV benchmark for evaluating semantic safety.

The introduction of Gemini Robotics 1.5 marks a significant step towards achieving artificial general intelligence (AGI) in the physical world, enabling robots to reason, plan, and use tools more effectively. The models are available to developers via the Gemini API in Google AI Studio, with Gemini Robotics 1.5 currently limited to select partners.
## Links

- [Gemini Robotics 1.5 Tech Report](https://storage.googleapis.com/deepmind-media/gemini-robotics/Gemini-Robotics-1-5-Tech-Report.pdf) : Technical report detailing the advancements and capabilities of Gemini Robotics 1.5.
- [Gemini Robotics ER 1.5](https://deepmind.google/models/gemini-robotics/gemini-robotics-er/) : Page detailing the Gemini Robotics-ER 1.5 model, which reasons about the physical world and creates detailed, multi-step plans to complete missions.

## Topics

![[topics/Model/Gemini Robotics]]

![[topics/Concept/Vision Language Action VLA Models]]

![[topics/Concept/Embodied Reasoning]]

![[topics/Concept/Agentic Capabilities]]