---
type: Concept
---

Source Replayability refers to the ability of a data source to provide historical data upon request. A replayable source can retrieve data from any past point in time, which is crucial for backfills and ensuring data consistency. Examples of replayable sources include event streams and database transaction logs. Non-replayable sources, such as application tables and APIs, only provide the current state of data. Ensuring replayability can involve dumping data into a raw area, which then acts as a replayable source.