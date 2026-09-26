---
already_read: false
link: https://www.vldb.org/pvldb/vol19/p4953-fernandez-moctezuma.pdf
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-09-26'
---

https://www.vldb.org/pvldb/vol19/p4953-fernandez-moctezuma.pdf

## Summary

The Dataflow Model paper's retrospective reveals that its core principles (event time, rejecting completeness, and strong consistency) aged well, but its interface (windowing, triggers, retractions) was over-engineered, with the real solution being declarative, table-centric streaming built on database foundations.

**What aged well**
- Event time vs. processing time became foundational vocabulary in streaming systems.
- Strong consistency became non-negotiable, ending the Lambda Architecture era.
- Rejecting completeness as a practical assumption proved correct for unbounded data.

**What aged poorly**
- Windowing and triggering were overcomplicated; users mostly needed simple time-bucket grouping and periodic/watermark-based firing.
- User-facing retractions were rarely used as designed; they belong as internal engine mechanisms, not user-facing protocols.
- The stream-centric worldview missed the duality of streams and tables (changelogs vs. snapshots).

**Key misses**
- Streams and tables are two representations of the same object (a time-varying relation), not separate concepts.
- SQL and incremental view maintenance (from database literature) were the right tools but underappreciated.
- The batch vs. streaming debate was semantic: engines differ, but semantics (bounded/unbounded) unify them.

**Evolution of completeness**
- Watermarks (stream-centric) and snapshot-consistent refresh (table-centric) emerged as two successful approaches.
- Declared constraints on change (finalization, ordering, monotonicity) generalize watermarks beyond time.

**Interface lessons**
- Users want declarative interfaces (SQL, materialized views) with freshness contracts, not imperative streaming mechanics.
- Target lag (e.g., `max_staleness`, `FRESHNESS`) replaced complex trigger languages.
- Retractions are critical internally (for incremental view maintenance) but should be hidden from users.

**Industry trends**
- Low-latency demand bifurcated: OLTP needs milliseconds, OLAP (analytics) thrives at seconds-to-minutes.
- Fault tolerance became commoditized (checkpointing, logs, durable storage).
- Materialized views (Materialize, Snowflake Dynamic Tables, Delta Live Tables) made streaming disappear for analytics.

**What to leave in/out**
- **Leave in**: Event time, consistency, unaligned windows (for sessions), engine independence.
- **Leave out**: Most trigger complexity, user-facing retractions, stream-only worldview.

**Future directions**
- Cycles (for stateful workflows) and richer contracts (latency, durability, cost) are needed beyond analytics.
- A unified model for arbitrary computation (not just relational) could make all streaming disappear, not just analytics.

## Links



## Topics

![[topics/Model/Dataflow Model]]

![[topics/Concept/Event Time]]

![[topics/Concept/Watermarks]]

![[topics/Concept/Materialized View]]

![[topics/Concept/Incremental Data Processing]]

![[topics/Platform/Google Cloud Dataflow]]

![[topics/Concept/Streams and Tables Duality]]

![[topics/Concept/Declared Constraints on Change]]

![[topics/Tool/Apache Flink]]

![[topics/Platform/Apache Beam]]