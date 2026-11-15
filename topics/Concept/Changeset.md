---
type: Concept
---

A changeset is the fundamental unit of work in Scion, representing a commit-like entry in a write-ahead log. Unlike git commits, which store pointers to trees, a changeset records a list of changed files relative to its first parent and uses content-addressed pointers to compressed file contents in blob storage. Changesets are created server-side, are instantly available, and enable high-throughput operations without packfiles or locking. They serve as the basis for derived data structures like file blame and path history.