---
already_read: true
link: https://sqlmodel.tiangolo.com/tutorial/automatic-id-none-refresh/
read_priority: 1
source: The Batch
tags:
- Data_Engineering
type: Content
upload_date: '2024-11-10'
---

https://sqlmodel.tiangolo.com/tutorial/automatic-id-none-refresh/
## Summary

The content discusses the use of SQLModel in Python for managing database interactions, focusing on automatic IDs, handling None defaults, and refreshing data. Key points include:

- **Automatic IDs**: The `id` field is defined as a primary key and can be `None` in Python code, allowing for flexibility when creating new instances of models.
- **Session Management**: When objects are added to a session, they are not immediately saved to the database. The session commits changes only when explicitly instructed, which optimizes performance.
- **Data Expiration**: After committing a session, objects are marked as "expired," meaning they do not contain the latest data until refreshed. Accessing attributes triggers a refresh from the database.
- **Explicit Refreshing**: Developers can manually refresh objects using `session.refresh(object)` to ensure they have the latest data.
- **Post-Session Behavior**: Data can still be accessed after the session closes, as the objects retain their state, but they may not reflect the most current database values unless refreshed.

The content emphasizes understanding how SQLModel and SQLAlchemy manage data synchronization between Python objects and the database, highlighting potential pitfalls and best practices for effective data handling.
## Links

1. [SQLModel GitHub Repository](https://github.com/fastapi/sqlmodel) - The official repository for SQLModel, which provides the source code and documentation for this library.
2. [SQLAlchemy Documentation](https://docs.sqlalchemy.org/en/14/) - Comprehensive documentation for SQLAlchemy, the underlying ORM used by SQLModel for database interactions.
3. [FastAPI Documentation](https://fastapi.tiangolo.com/) - Documentation for FastAPI, which is closely related to SQLModel and often used in conjunction with it for building APIs.
4. [Pydantic Documentation](https://pydantic-docs.helpmanual.io/) - Documentation for Pydantic, which is used for data validation and settings management in SQLModel.
5. [SQLite Documentation](https://www.sqlite.org/docs.html) - Official documentation for SQLite, the database used in the examples provided in the SQLModel tutorial.
## Topics

![](topics/Library/SQLModel)

![](topics/Concept/Session%20Management)

![](topics/Concept/Object%20Relational%20Mapping%20ORM)

![](topics/Concept/Data%20Expiration)

![](topics/Concept/Database%20Transactions)