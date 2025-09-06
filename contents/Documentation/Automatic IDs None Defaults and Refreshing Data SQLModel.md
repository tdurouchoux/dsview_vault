---
already_read: true
link: https://sqlmodel.tiangolo.com/tutorial/automatic-id-none-refresh/
read_priority: 1
relevance: 0
source: The Batch
tags:
- Development_tool
type: Content
upload_date: '2024-11-10'
---

https://sqlmodel.tiangolo.com/tutorial/automatic-id-none-refresh/
## Summary

The content discusses the interaction between SQLModel, SQLAlchemy, and a database, focusing on how data is synchronized between Python objects and the database. Key points include:

1. **Automatic IDs and None Defaults**:
   - Primary keys in the database cannot be NULL, but in Python code, they can be set to None using `int | None` and `Field(default=None)`.

2. **Session and Database Interaction**:
   - Objects are added to a session but not immediately saved to the database.
   - The session commits changes to the database, generating SQL statements to insert data.

3. **Data Synchronization**:
   - After committing, objects are marked as "expired" and appear empty when printed.
   - Accessing an attribute triggers a refresh, fetching the latest data from the database.

4. **Explicit Refresh**:
   - The `session.refresh(object)` method can be used to explicitly refresh an object's data from the database.

5. **Session Lifecycle**:
   - The session can be closed, and objects retain their data even after the session is closed.

6. **Recap**:
   - The content emphasizes understanding how sessions manage data synchronization and the importance of refreshing data to avoid issues.

The tutorial provides a detailed walkthrough of creating, committing, and refreshing data, illustrating the underlying mechanisms with SQL statements and Python code examples.
## Links

- [SQLModel GitHub Repository](https://github.com/fastapi/sqlmodel) : The GitHub repository for SQLModel, a library that combines SQLAlchemy for database operations and Pydantic for data validation, providing an easy-to-use interface for working with databases in Python.

## Topics

![](topics/Library/SQLModel)

![](topics/Library/SQLAlchemy)