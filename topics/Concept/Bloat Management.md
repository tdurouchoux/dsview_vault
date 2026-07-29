---
type: Concept
---

Bloat in PostgreSQL refers to the accumulation of dead tuples (rows marked for deletion but not yet removed) and partially filled disk pages, which can degrade database performance and increase storage usage. Effective bloat management involves tuning autovacuum settings, using tools like pg_repack, and monitoring table and index sizes to ensure optimal database performance.