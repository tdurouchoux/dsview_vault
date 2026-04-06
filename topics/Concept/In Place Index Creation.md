---
type: Concept
---

In-place index creation is a technique for adding metadata, such as vector indexes, to existing Parquet files without rewriting the entire file. This is achieved by appending the index to the end of the file's metadata section and updating the footer. The approach ensures compatibility with standard Parquet readers while enabling advanced features like vector search without altering the underlying data pages.