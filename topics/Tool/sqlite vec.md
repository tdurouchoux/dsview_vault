---
type: Tool
---

sqlite-vec is a vector search SQLite extension that allows for storing and querying float, int8, and binary vectors in vec0 virtual tables. It is written in pure C, has no dependencies, and runs anywhere SQLite runs, including Linux, MacOS, Windows, in the browser with WASM, and on Raspberry Pis. It supports storing non-vector data in metadata, auxiliary, or partition key columns.