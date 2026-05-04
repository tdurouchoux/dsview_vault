---
type: Concept
---

A lookup table (LUT)-based approximation is a technique used to approximate complex mathematical functions (e.g., exponentials) using precomputed values stored in a table. In Talos V2, this method is employed to approximate the exponential function in the softmax operation, reducing the computational overhead and hardware complexity compared to a direct implementation. This approach is particularly useful in hardware design, where combinational logic for complex functions can be resource-intensive and challenging to optimize.