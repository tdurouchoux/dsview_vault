---
already_read: true
link: https://github.com/buva7687/sql-crack
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Data_Visualization
type: Content
upload_date: '2026-03-31'
---

https://github.com/buva7687/sql-crack
## Summary

**SQL Crack** is a VS Code extension that visualizes SQL queries as interactive execution flow diagrams, aiding in understanding complex queries, tracking data lineage, and identifying optimization opportunities. Key features include:

- **Query Visualization**: Step-by-step execution flow, multi-query support, column lineage, CTE/subquery expansion, and query comparison.
- **Workspace Analysis**: Dependency graphs, data lineage, and impact analysis across SQL projects.
- **Smart Analysis**: Quality warnings, performance hints, and a performance score (0-100).
- **Parser Reliability**: Supports multiple dialects, handles large files, and includes fallback mechanisms.
- **Interactive Navigation**: Click-to-navigate, breadcrumb trails, search, and editor sync.
- **Layout & Export**: Multiple layout options, auto-refresh, and export formats (PNG, SVG, Mermaid.js).

**Supported Dialects**: MySQL, PostgreSQL, SQL Server, Snowflake, BigQuery, and more.

**Installation**: Available via VS Code Marketplace or from source.

**Usage**: Visualize queries via the editor title bar, command palette, or context menu.

**Configuration**: Customizable settings for dialects, layouts, auto-refresh, and more.

**Privacy**: Fully local, no telemetry, and open-source.

**Roadmap**: Includes diff-aware visualization, dbt integration, and performance regression detection.

**Contributions**: Open to community contributions via pull requests.

**Tech Stack**: TypeScript-based, leveraging tools like `node-sql-parser` and `dagre` for parsing and graph layout.
## Links

- [SQL Crack on Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=buvan.sql-crack) : Official Visual Studio Marketplace page for the SQL Crack extension, providing installation instructions, features, and user reviews.
- [SQL Crack on Open VSX Registry](https://open-vsx.org/extension/buvan/sql-crack) : Open VSX Registry page for the SQL Crack extension, an open-source alternative for installing the tool.
- [JSON Crack](https://jsoncrack.com/) : A tool inspired by SQL Crack for visualizing JSON data as interactive graphs, providing context for SQL Crack's design and functionality.
- [node-sql-parser](https://github.com/taozhi8833998/node-sql-parser) : GitHub repository for node-sql-parser, the SQL parsing library used by SQL Crack, relevant for developers interested in its technical implementation.
- [dagre.js](https://github.com/dagrejs/dagre) : GitHub repository for dagre.js, a JavaScript library for directed graph layout used by SQL Crack to render SQL query flow diagrams.

## Topics

![[topics/Tool/SQL Crack]]

![[topics/Library/node sql parser]]

![[topics/Library/dagre]]

![[topics/Platform/Visual Studio Code VS Code]]

![[topics/Concept/SQL Query Visualization]]

![[topics/Concept/Data Lineage and Provenance]]

![[topics/Concept/Query Optimization]]

![[topics/Concept/Workspace Dependency Analysis]]

![[topics/Concept/CTE Common Table Expression Expansion]]

![[topics/Concept/AST Abstract Syntax Tree]]