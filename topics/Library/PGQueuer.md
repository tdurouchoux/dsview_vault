---
type: Library
---

A lightweight, high-performance job queue library for Python that leverages PostgreSQL’s built-in features for background task management. It uses LISTEN/NOTIFY for real-time updates and FOR UPDATE SKIP LOCKED for concurrency control. PGQueuer supports scheduling recurring tasks with cron-like expressions, handling large job batches, and provides a real-time monitoring dashboard for tracking job queue statuses.