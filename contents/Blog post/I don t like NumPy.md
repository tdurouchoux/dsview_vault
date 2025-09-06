---
already_read: false
link: https://dynomight.net/numpy/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Python
- Data_Analysis
type: Content
upload_date: '2025-05-28'
---

https://dynomight.net/numpy/
## Summary

The author expresses a critical view of NumPy, a popular Python library for numerical computations, despite its widespread use and influence on machine learning libraries like PyTorch. The main points of criticism include:

1. **Complexity in Simple Operations**: While NumPy makes simple operations easy, more complex operations, such as solving systems of equations for multiple matrices and vectors, become convoluted and non-intuitive. The author highlights the lack of clear documentation and the need for trial and error to achieve the desired results.

2. **Broadcasting Issues**: NumPy's broadcasting feature, which automatically expands dimensions for arithmetic operations, is criticized for being non-explicit and non-legible. The author argues that broadcasting leads to ambiguity and requires users to constantly figure out which broadcasting convention is being applied.

3. **Indexing Complexity**: NumPy's indexing system is described as overly complex and error-prone. The author provides examples of indexing operations with unexpected results and notes that even advanced AI models struggle to predict the shapes of arrays resulting from these operations.

4. **Function Design Flaws**: The design of NumPy functions, such as `np.linalg.solve`, is criticized for being confusing and inconsistent. The author points out that NumPy's approach to handling different array shapes and dimensions leads to a combinatorial number of cases, making it difficult for users to apply functions correctly.

5. **Lack of Abstraction**: The author argues that NumPy does not support abstraction well, making it difficult to build complex operations from simpler ones. This is illustrated through an example of implementing multi-head attention in a language model, where the vectorized version is described as "bewildering" compared to a loop-based approach.

The author concludes by suggesting that NumPy is "the worst array language other than all the other array languages" and hints at having a better alternative in mind, which will be discussed in a future post. The overall critique emphasizes the need for a more intuitive, explicit, and legible array language that retains NumPy's power while eliminating its sharp edges.
## Links

- [NumPy Documentation](https://numpy.org/doc/stable/reference/generated/numpy.linalg.solve.html) : The official documentation for NumPy's linear algebra functions, including the solve function.
- [NumPy Broadcasting](https://numpy.org/doc/stable/user/basics.broadcasting.html) : The official documentation for NumPy's broadcasting mechanism.
- [NumPy Indexing](https://numpy.org/doc/stable/user/basics.indexing.html) : The official documentation for NumPy's indexing mechanism.

## Topics

![](topics/Library/NumPy)