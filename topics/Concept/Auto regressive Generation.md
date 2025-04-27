---
date: '2024-09-04'
type: Concept
---

Auto-regressive generation is a method where a model generates outputs sequentially, conditioning on previously generated outputs. This technique is pivotal in scenarios like video generation and time-series forecasting. In GameNGen, the auto-regressive approach is utilized to predict successive frames in a game simulation, although it poses challenges like error accumulation and sampling divergence which the model addresses through methods like noise augmentation.