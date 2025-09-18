---
already_read: false
link: https://dynomight.net/numpy/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Python
- Development_tool
type: Content
upload_date: '2025-05-28'
---

https://dynomight.net/numpy/
## Summary

The author expresses a love-hate relationship with NumPy, a popular Python library for array computations, highlighting its elegance for simple tasks but criticizing its complexity and lack of clarity for more intricate operations. The main issues discussed include:

1. **Complexity with Higher-Dimensional Arrays**: NumPy's simplicity diminishes when dealing with multi-dimensional arrays. The author illustrates this with an example of solving a system of linear equations for each slice of a 3D array, showing how NumPy's lack of clear documentation and intuitive methods makes this task confusing.

2. **Broadcasting and Indexing**: The author criticizes NumPy's broadcasting and indexing mechanisms, which can lead to non-intuitive behaviors and require users to understand complex rules. Examples are provided where even advanced AI models struggle to predict the shapes of arrays resulting from certain indexing operations.

3. **Function Design**: NumPy's functions, like `np.linalg.solve`, are criticized for their lack of consistency and clarity. The author argues that NumPy's design makes it difficult to apply functions to specific dimensions of larger arrays, forcing users to rewrite functions from scratch.

4. **Self-Attention Example**: The author provides an example of implementing self-attention, a core component of modern language models, highlighting the complexity and lack of readability in NumPy's approach compared to a hypothetical loop-based implementation.

The author concludes by suggesting that NumPy's design flaws stem from its reliance on broadcasting and the removal of indices, which leads to a lack of clarity and usability. They hint at having a better solution but defer discussing it to a future post.
## Links

- [NumPy einsum documentation](https://numpy.org/doc/stable/reference/generated/numpy.einsum.html) : Documentation for the NumPy einsum function, which is used for Einstein summation.
- [NumPy broadcasting documentation](https://numpy.org/doc/stable/user/basics.broadcasting.html) : Documentation for NumPy broadcasting, which is a powerful mechanism for vectorizing array operations, as discussed in the article.
- [NumPy tensordot documentation](https://numpy.org/doc/stable/reference/generated/numpy.tensordot.html) : Documentation for the NumPy tensordot function, which is used for tensor contractions.

## Topics

![[topics/Library/JAX]]

![[topics/Library/NumPy]]

![[topics/Library/CuPy]]

![[topics/Library/Einops]]