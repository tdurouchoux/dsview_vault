---
already_read: true
link: https://arxiv.org/pdf/2408.14837
read_priority: 1
source: Alpha signal
tags:
- Generative_AI
- Computer_Vision
type: Content
upload_date: '2024-09-04'
---

![](artefacts/2408.14837)
## Summary

GameNGen is a novel game engine that utilizes a neural model to enable real-time interaction with complex environments, specifically demonstrated through the classic game DOOM. It achieves over 20 frames per second on a single TPU, with next-frame predictions showing a PSNR of 29.4, comparable to lossy JPEG compression. The training process consists of two phases: first, a reinforcement learning (RL) agent learns to play the game, and second, a diffusion model is trained to predict the next frame based on past frames and actions.

Key technical points include:
- GameNGen operates by simulating an interactive environment, where it maintains a latent state space, action space, and transition probabilities.
- The generative diffusion model is conditioned on the RL agent's recorded trajectories, allowing it to generate frames autoregressively.
- To mitigate issues with auto-regressive generation, noise augmentation is applied during training, which helps maintain quality over longer sequences.
- The model's architecture is based on an augmented version of Stable Diffusion, adapted for game simulation.

Results indicate that GameNGen can produce high-quality simulations that are often indistinguishable from actual gameplay, with human raters only slightly better than random chance at identifying real versus simulated clips. The model's limitations include a constrained memory that restricts the context length to about 3 seconds, which can affect performance in more complex scenarios.

Future work aims to explore the application of GameNGen to other games, improve memory utilization, and optimize performance for higher frame rates on consumer hardware. This research represents a significant step towards a new paradigm in game development, where games could be generated from neural models rather than traditional coding methods.
## Topics

- [[topics/Platform/GameNGen]]
- [[topics/Model/Diffusion Models]]
- [[topics/Concept/Interactive Data Simulation]]
- [[topics/Concept/Reinforcement Learning]]
- [[topics/Concept/Auto-regressive Generation]]