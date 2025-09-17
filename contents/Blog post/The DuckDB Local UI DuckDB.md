---
already_read: false
link: https://duckdb.org/2025/03/12/duckdb-ui.html
read_priority: 5
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2025-03-12'
---

https://duckdb.org/2025/03/12/duckdb-ui.html
## Summary

The DuckDB team and MotherDuck have released a local UI for DuckDB, integrated as part of the ui extension. This UI aims to simplify the use of DuckDB by providing a full-featured local web interface, addressing the limitations of the existing CLI and third-party tools.

Key features of the DuckDB UI include:

- **Databases**: View and explore attached databases, tables, and views.
- **Table Summary**: Get detailed summaries of tables, including row counts, column types, and data profiles.
- **Notebooks**: Organize work into named notebooks with syntax highlighting and autocomplete for SQL queries.
- **Column Explorer**: Gain insights into query results through a detailed column summary.
- **MotherDuck Integration**: Opt-in to connect with MotherDuck for cloud data warehouse capabilities.
- **Local Execution**: All queries run locally, ensuring data privacy.

The UI is implemented as a DuckDB extension, embedding a localhost HTTP server for low-latency performance. It is open-source, with the frontend code currently under review for open-sourcing. The team is actively working on improvements, including offline support and opening the client-server protocol.

For support or feedback, users can file issues or join the DuckDB Discord or MotherDuck Community Slack.
## Links

- [DuckDB GitHub Repository](https://github.com/duckdb/duckdb) : The GitHub repository for DuckDB, where you can find the source code, issues, and contributions related to DuckDB.
- [DuckDB UI GitHub Repository](https://github.com/duckdb/duckdb-ui) : The GitHub repository for the DuckDB UI extension, which includes the source code and documentation for the UI.

## Topics

![](topics/Platform/MotherDuck)

![](topics/Library/DuckDB)