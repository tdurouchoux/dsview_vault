---
type: Concept
---

Compound indexes are multi-column indexes in PostgreSQL that improve query performance by allowing the database to satisfy queries using a single index lookup. Properly designing compound indexes involves aligning the index columns with the most common query filters and ORDER BY clauses to maximize efficiency.