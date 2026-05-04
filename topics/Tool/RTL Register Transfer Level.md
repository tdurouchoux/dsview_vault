---
type: Tool
---

RTL is a design abstraction used in hardware engineering to describe the flow of digital signals between hardware registers and the logical operations performed on those signals. It bridges the gap between high-level behavioral descriptions and low-level circuit implementations. In the context of Talos V2, RTL is used to explicitly define the inference path of a transformer model, converting mathematical operations into hardware components like memories, counters, state transitions, accumulators, lookup tables, and multicycle arithmetic engines. This approach enables direct hardware implementation and optimization of neural network models.