---
type: Platform
---

Scion is a proprietary version control system developed by Anthropic to replace git for managing their massive monorepo. It is designed specifically for agent-scale software development, where clients (e.g., AI agents) are always online and require high-throughput, scalable source control operations. Scion's architecture is client-server based, with a server handling all core operations (e.g., commits, merges, diffs) and clients maintaining minimal local state. It uses changesets (write-ahead log entries) to record file changes, supports derived data structures for operations like blame and path history, and is horizontally scalable with no fully materialized repository copies.