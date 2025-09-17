---
type: Library
---

Fugue is a library that simplifies the usage of distributed computing frameworks like Spark, Dask, and Ray. It aims to minimize the amount of framework-specific code users need to learn, providing a consistent interface for distributed computing. Fugue supports both Python and SQL, allowing users to write code in a familiar language and then execute it on various distributed backends. It also ensures consistency in operations like NULL handling across different backends, making it easier to prototype locally and scale out to larger clusters.