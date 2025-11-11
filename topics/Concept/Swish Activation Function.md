---
type: Concept
---

The Swish activation function, also known as the sigmoid linear unit (SiLU), is a smooth, non-linear activation function used in neural networks. It is defined as the product of the input and its sigmoid function, i.e., f(x) = x * sigmoid(x). Swish is computationally cheaper than GELU (Gaussian Error Linear Unit) and has been adopted in many modern large language models (LLMs) due to its efficiency and performance benefits. Swish is often preferred over GELU in newer architectures because it is simpler to compute and can lead to better model performance, although the differences are often within standard error margins.