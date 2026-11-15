---
type: Tool
---

scion-cache is a regional cache server in Scion's architecture that stores and serves source control objects (trees and blobs) directly from memory in their disk format. It acts as a tiered cache between the client (via scion-daemon) and the authoritative scion-servers, enabling high hit rates (>99%) and low-latency access to frequently requested objects. The cache servers stream objects to clients without performing delta compression, reducing CPU overhead and improving scalability.