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
- **Session Management**: When objects are added to a session, they remain in a pending state until the session is committed. After committing, objects are marked as "expired" until their attributes are accessed, which triggers a refresh from the database.
- **Explicit Refreshing**: Users can manually refresh an object using `session.refresh(object)` to ensure it has the latest data from the database.
- **Data Synchronization**: The session manages the synchronization between the in-memory objects and the database, automatically fetching updated data when attributes are accessed.
- **Practical Example**: The content includes a detailed code example demonstrating the creation of hero instances, adding them to a session, committing changes, and refreshing data.

Overall, the material emphasizes understanding how SQLModel interacts with databases, the importance of managing session states, and the implications of data expiration.
## Links

1. [SQLModel GitHub Repository](https://github.com/fastapi/sqlmodel) - The official repository for SQLModel, which provides a way to interact with SQL databases using Python.
2. [SQLAlchemy Documentation](https://docs.sqlalchemy.org/en/14/) - Comprehensive documentation for SQLAlchemy, the underlying library used by SQLModel for database interactions.
3. [FastAPI Documentation](https://fastapi.tiangolo.com/) - Documentation for FastAPI, which is often used in conjunction with SQLModel for building APIs.
4. [Pydantic Documentation](https://pydantic-docs.helpmanual.io/) - Documentation for Pydantic, which is used for data validation and settings management in Python, and is integrated with SQLModel.
5. [Python Typing Documentation](https://docs.python.org/3/library/typing.html) - Official documentation on Python's typing system, which is relevant for understanding type hints like `Optional` used in SQLModel.
## Topics

- [[topics/Library/SQLModel]]
- [[topics/Concept/Session Management]]
- [[topics/Concept/Object Relational Mapping (ORM)]]
- [[topics/Concept/Data Expiration]]
- [[topics/Concept/Database Transactions]]