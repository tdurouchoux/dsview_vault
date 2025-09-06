---
already_read: true
link: https://arxiv.org/pdf/2408.14837
read_priority: 1
relevance: 0
source: Alpha signal
tags:
- Large_Language_Model
- Computer_Vision
type: Content
upload_date: '2024-09-04'
---

https://arxiv.org/pdf/2408.14837
## Summary

The paper introduces GameNGen, a neural model-based game engine that can simulate the classic game DOOM in real-time with high quality. The model is trained in two phases: first, an RL-agent learns to play the game and records training sessions; second, a diffusion model is trained to predict the next frame based on past frames and actions. Key technical points include the use of noise augmentation to mitigate auto-regressive drift and decoder fine-tuning to improve visual fidelity. The model achieves a PSNR of 29.4, comparable to lossy JPEG compression, and human raters struggle to distinguish between short clips of the simulation and the actual game. The paper also discusses limitations, such as the model's limited memory and the differences between the agent's behavior and human players, and suggests future work to address these issues. The broader impact and societal implications of GameNGen are also considered.
## Links


## Topics

![](topics/Model/GameNGen)

![](topics/Concept/Interactive%20World%20Simulation)

![](topics/Concept/Noise%20Augmentation)

![](topics/Concept/Latent%20Decoder%20Fine%20Tuning)