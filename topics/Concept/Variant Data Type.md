---
type: Concept
---

The variant data type is a flexible, binary-encoded format for storing semi-structured data. It supports a wider range of types than JSON (e.g., DATE, TIMESTAMP) and enables efficient querying through techniques like shredding (converting nested fields into primitive types). Variant types are optimized for performance, including filter and projection pushdown, and are considered a superior alternative to JSON for semi-structured data in databases.