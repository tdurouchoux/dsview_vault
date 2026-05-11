---
type: Concept
---

Dataloaders in GraphQL are utility libraries designed to address the N+1 query problem, where a client makes multiple requests to fetch related data inefficiently. Dataloaders batch multiple requests into a single request, reducing the number of database or API calls. They also provide caching mechanisms to avoid redundant computations, improving performance and efficiency in data fetching.