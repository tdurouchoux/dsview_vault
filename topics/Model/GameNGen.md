---
type: Model
---

GameNGen is a generative diffusion model designed to simulate complex video games, specifically DOOM, in real-time. It enables interactive simulation of game environments with high visual quality and stability over extended play sessions. The model is trained in two phases: first, an RL agent learns to play the game, and second, a diffusion model is trained to predict the next frame based on past frames and actions. GameNGen achieves a PSNR of 29.4, comparable to lossy JPEG compression, and maintains stability over multi-minute play sessions at 20 frames per second on a single TPU.