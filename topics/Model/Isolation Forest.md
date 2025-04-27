---
date: '2025-01-08'
type: Model
---

Isolation Forest is an anomaly detection technique that specifically focuses on isolating outliers using tree structures. The premise is that anomalies are easier to isolate compared to normal data points, thus the method constructs a forest of random trees where the path length from the root to a leaf is utilized to identify anomalies. Shorter average path lengths indicate potential outliers.