---
already_read: true
link: https://blog.google/innovation-and-ai/models-and-research/google-deepmind/gemini-robotics-er-2/
read_priority: 0
relevance: 5
source: The Batch
tags:
- Large_Language_Model
type: Content
upload_date: '2026-08-04'
---

https://blog.google/innovation-and-ai/models-and-research/google-deepmind/gemini-robotics-er-2/

## Summary

Gemini Robotics ER 2 is Google’s latest embodied reasoning model for robotics, enabling real-time spatial reasoning, multi-step task orchestration, and multi-robot collaboration.

**Core capabilities**
- Acts as a high-level "brain" for robots, handling reasoning while delegating motor control to lower-level VLA models.
- Processes continuous video feeds to track task progress, adapt to errors, and switch steps dynamically.
- Supports tool calling (e.g., Google Search, custom functions) and bidirectional streaming via the Gemini Live API for low-latency operation.

**Performance highlights**
- 57.4% accuracy on progress classification (5-tier granularity).
- 91.3% accuracy and 0.96s mean absolute distance on moment-finding tasks.
- 4x faster execution than competitors at a fraction of the compute cost.

**Key features**
- Multi-robot collaboration via shared semantic understanding (e.g., Apptronik Apollo 2 + Franka F3 Duo).
- Enhanced spatial intelligence: success/failure detection on raw video, generalized instrument reading (10+ types), and improved VQA.
- Safety improvements: top scores on Safety Instruction Following and Human Proximity benchmarks; halts robots near humans and resumes autonomously when clear.

**Availability**
- Public access via Gemini API, Google AI Studio, and private preview on Gemini Enterprise Agent Platform.
- Demo code and examples available on GitHub (e.g., Boston Dynamics Spot integration).

## Links

- [Gemini Robotics Overview - AI Google Dev Documentation](https://ai.google.dev/gemini-api/docs/robotics-overview) : Official documentation for the Gemini Robotics API, detailing how to integrate and use the Gemini Robotics ER 2 model for robotics applications via the Gemini API, Google AI Studio, or the Gemini Enterprise Agent Platform.
- [Gemini Robotics ER 2 Model Card](https://deepmind.google/models/model-cards/gemini-robotics-er-2/) : Technical model card for Gemini Robotics ER 2, providing detailed specifications, capabilities, and safety benchmarks for the model.
- [Gemini Live API Documentation](https://ai.google.dev/gemini-api/docs/live-api) : Documentation for the Gemini Live API, which enables bidirectional streaming for latency-sensitive robotics tasks, allowing real-time decision-making and action orchestration.
- [Gemini Robotics ER 2 Safety Technical Report](https://storage.googleapis.com/deepmind-media/gemini-robotics/Gemini-Robotics-2-Safety.pdf) : Technical report detailing the safety advancements and benchmarks of Gemini Robotics ER 2, including Safety Instruction Following and Human Proximity evaluations.
- [Gemini Robotics ER 2 GitHub Samples](https://github.com/google-gemini/robotics-samples/blob/main/Getting%20Started/gemini_robotics_er.ipynb) : GitHub repository containing sample code and notebooks for getting started with Gemini Robotics ER 2, including examples for configuring the model and integrating it with robotics APIs.


## Topics

![[topics/Model/Gemini Robotics]]

![[topics/Model/Gemini]]

![[topics/Platform/Gemini Enterprise Agent Platform]]

![[topics/Platform/Google AI Studio]]

![[topics/Concept/Embodied Reasoning]]

![[topics/Concept/Vision Language Action VLA Models]]