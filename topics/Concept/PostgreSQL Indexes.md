---
type: Concept
---

PostgreSQL indexes are special database objects designed to increase the speed of data access by allowing the database to read less data from the disk. They can also enforce constraints like primary keys, unique keys, and exclusion. Indexes are crucial for performance but do not speed up a query unless the query matches the columns and data types in the index. The query planner, a part of PostgreSQL, determines the best way to execute a query, considering statistics and predefined costs associated with each type of scan.