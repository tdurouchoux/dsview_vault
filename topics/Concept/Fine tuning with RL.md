---
type: Concept
---

Fine-tuning with reinforcement learning involves using reinforcement learning algorithms, such as Proximal Policy Optimization (PPO), to optimize the parameters of a language model based on the reward model. This process involves formulating the fine-tuning task as a reinforcement learning problem, where the policy is the language model, the action space is the vocabulary of the language model, and the observation space is the distribution of possible input token sequences. The reward function combines the preference model and a constraint on policy shift, and the update rule maximizes the reward metrics in the current batch of data.