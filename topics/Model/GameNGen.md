---
type: Model
---

GameNGen is a generative diffusion model designed to simulate complex video games, such as DOOM, in real-time. It is trained in two phases: first, an RL-agent learns to play the game and records training sessions; second, a diffusion model is trained to produce the next frame conditioned on past frames and actions. The model achieves high-quality simulation with a PSNR of 29.4 and runs at 20 frames per second on a single TPU. It uses noise augmentation to stabilize auto-regressive generation and fine-tunes the latent decoder to improve visual fidelity. GameNGen demonstrates the potential for neural models to power game engines, enabling real-time interaction with complex environments.