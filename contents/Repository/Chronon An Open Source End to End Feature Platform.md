---
already_read: true
link: https://chronon.ai/
read_priority: 1
relevance: 0
source: null
tags:
- Feature_Engineering
- Data_Engineering
type: Content
upload_date: '2025-01-02'
---

https://chronon.ai/
## Summary

Chronon is an open-source, end-to-end feature platform for ML teams, enabling easy creation, deployment, management, and monitoring of data pipelines for machine learning. It's maintained by Airbnb and Stripe.

**Key Features:**
- Data consumption from various sources (event streams, DB tables, etc.)
- Results production in both online (low-latency endpoints) and offline (Hive tables) contexts
- Real-time or batch accuracy (temporal or snapshot)
- Backfilling training sets from raw data
- Powerful Python API with SQL-like primitives
- Automated feature monitoring

**Example:**
The provided code example demonstrates a simple Chronon GroupBy, which aggregates metrics about a user's previous purchases in various windows. It creates user-level features by aggregating the number of purchases and purchase value, which can be used to automatically create offline datasets, feature serving endpoints, and data quality monitoring pipelines.

For more details, refer to the Quickstart Tutorial or the Creating Training Data section.
## Links

- [Chronon GitHub Repository](https://github.com/airbnb/chronon) : The GitHub repository for Chronon, an open-source end-to-end feature platform for machine learning.
- [Chronon Quickstart Tutorial](https://chronon.ai/getting_started/Tutorial.html) : A tutorial to get started with Chronon, covering the complete flow from generating training data to online serving.

## Topics

![[topics/Platform/Chronon]]