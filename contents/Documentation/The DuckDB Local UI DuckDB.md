---
already_read: false
link: https://duckdb.org/2025/03/12/duckdb-ui.html
read_priority: 5
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2025-03-12'
---

https://duckdb.org/2025/03/12/duckdb-ui.html
## Summary

The DuckDB Local UI is a new feature introduced in DuckDB v1.2.1, developed in collaboration with MotherDuck. It aims to simplify the user experience, allowing seamless interaction with DuckDB through a dedicated web interface. Users can start the UI from the command line using the `-ui` argument or through SQL with `CALL start_ui();`.

Key features of the DuckDB UI include:

- **Local Query Execution**: Queries are processed locally; data does not leave the user's computer. 
- **Database Management**: Users can view attached databases and explore tables and views.
- **Notebooks**: SQL scripts can be organized into notebooks with support for syntax highlighting and autocomplete.
- **Column Explorer**: Provides insights into query results with detailed column summaries.
- **MotherDuck Integration**: Allows users to connect to a cloud data warehouse for persistent data storage.

The UI is designed for performance, using native DuckDB capabilities and requiring minimal setup. It creates files in the `.duckdb` directory for user data management.

The UI is open-source, although the frontend code's licensing is under review. Future updates are expected to enhance features and offline capabilities. Feedback can be shared through community channels.
## Links

- [DuckDB GitHub Repository](https://github.com/duckdb/duckdb) : Official GitHub repository for DuckDB, containing source code and releases.
- [DuckDB Local UI GitHub Repository](https://github.com/duckdb/duckdb-ui) : GitHub repository for the DuckDB Local UI extension.
- [Getting Started with MotherDuck](https://motherduck.com/docs/getting-started/) : Documentation to help users understand how to get started using MotherDuck with DuckDB.
- [Server-sent Events Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events) : MDN Web Docs page explaining server-sent events, which are utilized in the DuckDB UI for real-time updates.
- [DuckDB Community Extensions](https://duckdb.org/community_extensions/) : Overview of various community-developed extensions and tools available for DuckDB.

## Topics

![](topics/Tool/DuckDB)

![](topics/Concept/User%20Interface%20UI%20for%20Databases)

![](topics/Concept/Interactive%20Notebooks)

![](topics/Concept/Local%20Execution%20of%20Queries)

![](topics/Concept/Data%20Exploration%20Tools)