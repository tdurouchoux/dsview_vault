---
type: Concept
---

A systolic array is a network of data processing units (DPUs) arranged in a grid, where data flows through the array in a rhythmic fashion, similar to a systolic heart. In Talos V2, a 16-lane streamed systolic matrix-vector tile is used to perform matrix-vector multiplications efficiently. This design allows for parallel processing of multiple output rows while streaming the input vector column by column, optimizing both throughput and resource utilization in the FPGA.