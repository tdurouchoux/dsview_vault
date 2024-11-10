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

- **Automatic IDs**: The `id` field is defined as a primary key and can be `None` in Python code, allowing for the creation of new instances without needing to set an ID initially.
- **Session Management**: When instances are added to a session and committed, they are marked as "expired" until refreshed. This means that accessing their attributes will trigger a database query to fetch the latest data.
- **Explicit Refreshing**: The `session.refresh(object)` method can be used to manually refresh an object's data from the database.
- **Data Synchronization**: The session ensures that the data in memory is synchronized with the database, automatically handling the expiration of objects and refreshing them as needed.

The content also includes code examples demonstrating how to create instances, add them to a session, commit changes, and refresh data, along with the expected outputs at each step. The overall takeaway emphasizes understanding how SQLModel and SQLAlchemy manage data states and interactions with the database.
## Links

1. [SQLModel GitHub Repository](https://github.com/fastapi/sqlmodel) - The official repository for SQLModel, which provides a way to interact with SQL databases using Python.
2. [SQLAlchemy Documentation](https://docs.sqlalchemy.org/en/14/) - Comprehensive documentation for SQLAlchemy, the underlying library that SQLModel is built upon, detailing how to manage database interactions.
3. [FastAPI Documentation](https://fastapi.tiangolo.com/) - Documentation for FastAPI, which is often used in conjunction with SQLModel for building APIs.
4. [Pydantic Documentation](https://pydantic-docs.helpmanual.io/) - Documentation for Pydantic, which is used for data validation and settings management in Python, and is integrated with SQLModel.
5. [SQLite Documentation](https://www.sqlite.org/docs.html) - Official documentation for SQLite, the database used in the examples, providing insights into its features and usage.
## Topics

- [[topics/Library/SQLModel]]
- [[topics/Concept/Session Management]]
- [[topics/Concept/Object Relational Mapping (ORM)]]
- [[topics/Concept/Data Refreshing]]
- [[topics/Concept/Primary Key Management]]