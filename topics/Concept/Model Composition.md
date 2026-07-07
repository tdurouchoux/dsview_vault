---
type: Concept
---

Model composition refers to the ability to combine multiple machine learning models and business logic into a single, cohesive application. This approach allows for building complex inference services where different models (e.g., preprocessing, segmentation, filtering) can be chained together programmatically. Ray Serve supports model composition using a programmable API, enabling developers to treat calls to different models as function calls, even when they run on different resources or machines.