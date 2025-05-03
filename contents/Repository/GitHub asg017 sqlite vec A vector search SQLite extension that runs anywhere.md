---
already_read: true
link: https://github.com/asg017/sqlite-vec
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2025-05-03'
---

https://github.com/asg017/sqlite-vec
## Summary

sqlite-vec is a lightweight SQLite extension designed for efficient vector search capabilities. It is a successor to sqlite-vss and allows users to store and query float, int8, and binary vectors using `vec0` virtual tables. Key features include:

- Written in pure C with no external dependencies, ensuring compatibility across multiple platforms (Linux, macOS, Windows, and browsers with WASM).
- Supports both metadata alongside vector data stored in auxiliary or partition key columns.

Installation is straightforward with support for various programming languages like Python, Node.js, Ruby, Go, and Rust. Users can perform operations such as inserting vectors in JSON or binary formats and executing KNN (K-Nearest Neighbor) style queries.

The project is part of Mozilla’s Builders initiative, backed by sponsors such as Fly.io and SQLite Cloud. It is still in its early pre-v1 stage, indicating potential for breaking changes.
## Links

- [sqlite-vec Go Bindings](https://pkg.go.dev/github.com/asg017/asg017/sqlite-vec-go-bindings/cgo) : Documentation for the Go bindings of the sqlite-vec extension.
- [sqlite-rembed](https://github.com/asg017/sqlite-rembed) : A project for generating text embeddings from remote APIs like OpenAI.
- [rqlite Documentation](https://rqlite.io/docs/guides/extensions/) : Guide on using extensions in rqlite, including sqlite-vec.
- [sqlite-vec PyPI Package](https://pypi.org/project/sqlite-vec/) : Official Python package page for sqlite-vec.
- [sqlite-lembed](https://github.com/asg017/sqlite-lembed) : Project for generating text embeddings locally from embedding models.

## Topics

![](topics/Library/sqlite%20vec)

![](topics/Concept/Vector%20Search)

![](topics/Tool/Datasette)

![](topics/Concept/K%20Nearest%20Neighbors%20KNN%20Querying)