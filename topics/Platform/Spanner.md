---
type: Platform
---

Spanner is a globally distributed, horizontally scalable database developed by Google, used by Scion to store authoritative source control data. In Scion's architecture, Spanner serves as the persistent storage layer for changesets and other metadata, while caches and servers handle read operations and derived data computation. Spanner's scalability and consistency properties enable Scion to avoid fully materialized repository copies and support high-throughput operations.