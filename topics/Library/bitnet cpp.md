---
type: Library
---

bitnet.cpp is an official inference framework specifically designed for 1-bit LLMs, such as BitNet b1.58. It provides a suite of optimized kernels that support fast and lossless inference of 1.58-bit models on both CPU and GPU architectures. The framework is designed to achieve significant speedups and energy efficiency improvements, making it suitable for running large language models on local devices. bitnet.cpp is built on top of the llama.cpp framework and incorporates Lookup Table methodologies pioneered in T-MAC.