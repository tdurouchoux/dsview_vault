---
already_read: true
link: https://dbml.dbdiagram.io/home/
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-05-19'
---

https://dbml.dbdiagram.io/home/
## Summary

DBML (Database Markup Language) is an open-source DSL for defining and documenting database schemas in a simple, readable format. It is declarative (unlike imperative SQL DDL) and database-agnostic, making it easier to design and maintain schemas.

Key features:
- **Syntax**: Supports tables, fields, enums, and relationships (e.g., `Ref: posts.user_id > users.id`).
- **Tools**: Includes a visualizer (dbdiagram.io), documentation builder (dbdocs.io), SQL playground (runsql.com), and CLI for SQL/DBML conversion.
- **Ecosystem**: Open-source with community contributions (parsers, plugins, converters) and integrations (e.g., Prisma, Django, Laravel).

Best practice: Store `database.dbml` in your project root for version control and collaboration.

Use case: Ideal for large projects needing clear, up-to-date database documentation and visualization.
## Links

- [DBML GitHub Repository](https://github.com/holistics/dbml) : The official GitHub repository for DBML (Database Markup Language), containing the open-source code, documentation, and resources for DBML. This is a core resource for developers looking to explore, contribute, or use DBML in their projects.
- [DBML Parser (PHP)](https://github.com/butschster/dbml-parser) : A PHP-based parser for DBML, enabling developers to programmatically work with DBML files. This is useful for integration with PHP-based projects or tools.
- [DBML Parser for Java](https://github.com/nilswende/dbml-java) : A Java-based DBML parser, allowing developers to parse and work with DBML files in Java applications. This expands DBML's usability into the Java ecosystem.
- [DBML Generator for Prisma Schema](https://github.com/notiz-dev/prisma-dbml-generator) : A tool to generate DBML schemas from Prisma Schema files. This is particularly useful for developers using Prisma who want to visualize their database structure in DBML format.
- [VSCode Plugin for DBML](https://marketplace.visualstudio.com/items?itemName=duynvu.dbml-language) : A Visual Studio Code plugin that provides syntax highlighting, autocompletion, and other features for DBML files. This enhances the development experience for users working with DBML in VSCode.

## Topics

![[topics/Tool/DBML Database Markup Language]]

![[topics/Platform/dbdiagram io]]

![[topics/Platform/dbdocs io]]

![[topics/Tool/DBML CLI]]

![[topics/Library/DBML JS Library]]

![[topics/Concept/Database Documentation as Code]]

![[topics/Concept/Database Agnostic Design]]