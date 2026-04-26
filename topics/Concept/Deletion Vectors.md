---
type: Concept
---

Deletion vectors are a feature in lakehouse formats that allow efficient tracking of deleted rows without physically removing data from files. They store deletion information in separate files (e.g., Puffin files in DuckLake) and enable time travel by preserving historical states. Deletion vectors reduce the overhead of small delete operations and improve performance for frequent updates.