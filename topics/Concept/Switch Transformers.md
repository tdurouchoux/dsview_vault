---
type: Concept
---

Switch Transformers are a type of transformer model that utilizes the Mixture of Experts (MoE) architecture to improve efficiency and scalability. In Switch Transformers, each input token is routed to a single expert based on the output of a gating network, which simplifies the routing process and reduces computational overhead. This approach allows for faster training and inference compared to traditional dense transformer models, as only a subset of the model's parameters are activated for each input. Switch Transformers have been shown to achieve significant speedups in pretraining and can be used for a variety of natural language processing tasks.