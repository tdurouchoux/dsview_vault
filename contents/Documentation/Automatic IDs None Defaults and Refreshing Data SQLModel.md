---
already_read: true
link: https://sqlmodel.tiangolo.com/tutorial/automatic-id-none-refresh/
read_priority: 1
relevance: 0
source: The Batch
tags:
- Data_Engineering
type: Content
upload_date: '2024-11-10'
---

https://sqlmodel.tiangolo.com/tutorial/automatic-id-none-refresh/
## Summary

This content focuses on using SQLModel for managing data in Python, specifically regarding the handling of automatic IDs, default values, and data refresh mechanisms. 

Key points include:
- The `id` field, marked as a primary key with `Field(primary_key=True)`, cannot be NULL in the database but can be set to `None` in Python using the `Optional` type.
- Data is added to the database using a `Session`, which collects changes until `commit()` is called to execute SQL commands.
- After committing, objects are marked as "expired," making their data stale until refreshed. Accessing their attributes triggers a refresh from the database to update the values.
- Explicit refreshes can also be performed using `session.refresh(object)` if needed.
- The importance of managing data consistency between the Python application and the database is emphasized.

The content also includes code examples demonstrating these concepts in practice. Overall, understanding these principles leads to better handling of database interactions and avoids common issues related to data freshness.
## Links

- [SQLModel GitHub Repository](https://github.com/fastapi/sqlmodel) : The official GitHub repository for SQLModel, where you can find the source code, issues, and documentation.

## Topics

![](topics/Library/SQLModel)

![](topics/Concept/Session%20Management)

![](topics/Concept/Data%20Expiration%20and%20Refreshing)

![](topics/Library/FastAPI)

![](topics/Concept/Object%20Relational%20Mapping%20ORM)