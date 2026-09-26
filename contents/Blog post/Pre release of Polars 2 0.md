---
already_read: true
link: https://pola.rs/posts/announcing-polars-2/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-09-26'
---

https://pola.rs/posts/announcing-polars-2/

## Summary

Polars 2.0 release candidate introduces major defaults and API improvements, focusing on performance and strictness.

**Key Changes**
- Streaming engine now default for LazyFrame queries, improving memory usage and performance (5x faster).
- Row-order no longer guaranteed for certain operations (join, group_by, unpivot) unless `maintain_order=True`.
- Users can opt-out of streaming engine via `pl.Config.set_engine_affinity("in-memory")` or per-query `collect(engine="in-memory")`.

**Stricter Behavior**
- `is_in` now raises errors for lossy type coercions (e.g., Int64 vs. Float64).
- Horizontal concat enforces equal lengths; use `how="horizontal_extend"` for padding.
- Removed ambiguous casts (e.g., enums/categoricals to integers) in favor of dedicated methods like `.cat.to(dtype)` or `.str.to_date()`.

**Error Handling**
- New exceptions (`AttributeRemovedError`, `ArgumentRemovedError`) guide users to updated APIs.
- Examples: `melt` → `unpivot`, `join_nulls` → `nulls_equal`.

**Future Roadmap**
- Out-of-core streaming, async pipelines, S3 reader optimizations, SQL improvements, and cost-based planning.

## Links

- [Polars 2.0 Migration Guide](https://docs.pola.rs/releases/upgrade/2/) : Official migration guide for upgrading to Polars 2.0, covering breaking changes, new defaults (e.g., streaming engine), and strictness improvements. Essential for users transitioning from Polars 1.x.
- [Polars Python API Reference](https://docs.pola.rs/py-polars/html/reference/) : Comprehensive reference documentation for the Polars Python API, including methods, parameters, and usage examples. Useful for understanding new features and API changes in Polars 2.0.
- [Polars Rust Documentation](https://docs.rs/polars/latest/polars/) : Documentation for the Polars Rust library, including core functionality and performance optimizations. Relevant for users leveraging Rust bindings or contributing to the project.
- [Polars User Guide](https://docs.pola.rs/user-guide/) : General user guide for Polars, covering core concepts, query execution, and best practices. Helpful for understanding the streaming engine and other 2.0 features.


## Topics

![[topics/Model/Streaming Engine]]

![[topics/Concept/Strict Type Handling]]

![[topics/Concept/Error Reporting]]

![[topics/Concept/Out of Core Support]]

![[topics/Concept/IO Plugin Design]]

![[topics/Library/Polars]]

![[topics/Concept/LazyFrame]]