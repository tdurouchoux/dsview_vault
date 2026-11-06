---
type: Concept
---

Reinforcement Learning for Calibrated Decisions (RLCD) is a proprietary training algorithm used by the Jev model. It is designed to optimize both the correctness of decisions and the calibration of the model's confidence estimates. Calibration ensures that the model's predicted probabilities align with the actual observed frequencies of outcomes. RLCD likely combines reinforcement learning with techniques to penalize miscalibrated confidence scores, encouraging the model to provide reliable uncertainty estimates alongside its predictions. This approach is inspired by related methods like Reinforcement Learning with Calibration Rewards (RLCR), which explicitly rewards accurate confidence estimates.