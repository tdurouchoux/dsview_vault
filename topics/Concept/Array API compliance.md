---
type: Concept
---

A mechanism for verifying that an array library adheres to the Python array API standard. Compliance is determined by checking for the presence of the `__array_namespace__` attribute in array objects, which provides access to the standardized API namespace. This ensures interoperability and portability across conforming implementations.