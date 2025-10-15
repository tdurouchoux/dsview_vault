---
type: Concept
---

Hill climbing is an optimization algorithm used in machine learning to iteratively improve a solution by making small, incremental changes. In the context of ensembling, hill climbing involves starting with a strong single model and systematically adding other models with different weights, keeping only those combinations that improve validation performance. This process continues until no further gains are observed. The provided text highlights the use of hill climbing to capture complementary strengths across different models, often leading to better performance than any single model. GPU acceleration is mentioned as a means to speed up the evaluation of thousands of weight combinations, making hill climbing practical for large-scale datasets.