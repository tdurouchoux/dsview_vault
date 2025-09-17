---
type: Concept
---

Python Slots are a feature that allows developers to optimize the creation and access of class attributes by defining a fixed set of attributes using __slots__. This feature replaces the internal dictionary (__dict__) used to store attributes with an array-like structure, improving attribute access time to O(1). Slots are useful for reducing memory usage and speeding up attribute access in classes with a large number of instances.