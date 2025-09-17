---
already_read: false
link: https://www.deepmind.com/blog/discovering-novel-algorithms-with-alphatensor
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2022-10-13'
---

https://www.deepmind.com/blog/discovering-novel-algorithms-with-alphatensor
## Summary

AlphaTensor, developed by DeepMind, is an AI system designed to discover novel, efficient, and provably correct algorithms for fundamental tasks like matrix multiplication. Here are the key points:

1. **Matrix Multiplication**: AlphaTensor focuses on matrix multiplication, a ubiquitous operation in modern computing with applications ranging from image processing to weather simulations.

2. **Game-Based Approach**: The problem of finding efficient algorithms is framed as a single-player game, where the goal is to zero out a three-dimensional tensor representing the algorithm's correctness.

3. **Reinforcement Learning**: AlphaTensor uses reinforcement learning to play this game, gradually improving and rediscovering historical algorithms like Strassen's, eventually surpassing human intuition to find faster algorithms.

4. **Efficiency Gains**: AlphaTensor has discovered algorithms that outperform human-designed ones, such as reducing the number of multiplications for specific matrix sizes and improving on Strassen's algorithm.

5. **Hardware Optimization**: The system can be adapted to find algorithms optimized for specific hardware, leading to 10-20% faster matrix multiplications on platforms like Nvidia V100 GPUs and Google TPU v2.

6. **Broader Implications**: The research highlights the potential of AI in advancing mathematical and computational research, guiding further studies in complexity theory, and optimizing various computational tasks.

7. **Future Applications**: AlphaTensor's flexibility in optimizing different objectives could lead to new applications in energy usage, numerical stability, and other fields, inspiring further AI-driven algorithmic discovery.

The paper emphasizes the transformative potential of AI in solving fundamental problems in mathematics and beyond, building on the success of AlphaZero in game-playing domains.
## Links

- [AlphaTensor GitHub Repository](https://github.com/deepmind/alphatensor) : The GitHub repository for AlphaTensor, providing access to the code and resources related to the AI system for discovering novel algorithms for matrix multiplication.
- [Nature Article on AlphaTensor](https://www.nature.com/articles/s41586-022-05172-4) : The Nature article detailing the research and findings of AlphaTensor, including its discovery of new algorithms for matrix multiplication.

## Topics

![](topics/Model/AlphaTensor)