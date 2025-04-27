---
already_read: true
link: https://arxiv.org/pdf/2408.14837
read_priority: 1
relevance: 0
source: Alpha signal
tags:
- AI_agent
type: Content
upload_date: '2024-09-04'
---

![](artefacts/2408.14837)
## Summary

GameNGen is a pioneering neural game engine that achieves real-time simulation of complex environments, specifically demonstrated using the classic game DOOM. It operates at 20 frames per second on a single TPU and effectively generates gameplay trajectories over extended sessions, maintaining high visual quality with PSNR values nearing those of lossy JPEG compression.

Key technical points include:
- GameNGen utilizes a two-phase training process: firstly, a reinforcement learning (RL) agent learns to play the game, recording its actions and observations; secondly, a diffusion model predicts the next frame based on the previous frames and actions.
- Conditioning augmentations are employed to stabilize auto-regressive generation over long sequences, while fine-tuning the decoder improves image fidelity.
- The model is capable of simulating game logic, such as updating health and ammo, and has proven effective at maintaining coherence over multiple frames, despite the potential for sampling divergence.

Challenges identified include:
- Limitations in memory, restricting the model's historical context to a little over three seconds, which may affect performance in complex scenarios.
- The RL agent's playstyle does not fully replicate human behavior, which can introduce inaccuracies.

Future work aims to improve memory limitations, explore application to other games, and enhance the model's capacity to generate novel game experiences. Overall, GameNGen represents a significant step towards a new paradigm in game development, transitioning from traditional code-based creation to neural network-driven generation.
## Topics

![](topics/Model/GameNGen)

![](topics/Concept/Diffusion%20Models)

![](topics/Concept/Reinforcement%20Learning)

![](topics/Platform/TPU)

![](topics/Concept/Auto%20regressive%20Generation)

![](topics/Concept/Training%20Data%20Collection%20via%20Agent%20Play)