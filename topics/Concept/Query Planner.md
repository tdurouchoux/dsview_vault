---
type: Concept
---

The query planner, also known as the query optimizer, is a component in PostgreSQL responsible for determining the best execution strategy for a query. It uses statistics and predefined costs associated with each type of scan to make its decisions. The query planner can consider using indexes to speed up query execution, but it may also prefer a sequential scan if the query returns a large percentage of the table. The query planner's behavior can be complex and is influenced by various factors, including the presence of indexes and the specific query conditions.