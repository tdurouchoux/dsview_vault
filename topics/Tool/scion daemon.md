---
type: Tool
---

The scion-daemon is a client-side component of Scion that acts as a local cache and proxy for source control operations. It stores objects for the entire node, communicates with regional cache servers (scion-cache), and handles sparse or virtualized checkouts by only materializing files on demand. The daemon abstracts the cache topology from the client, enabling efficient reuse of objects across jobs on the same node and reducing the need for full repository checkouts.