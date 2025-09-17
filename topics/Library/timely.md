---
type: Library
---

The `timely` library is a Rust crate that implements the timely dataflow model. It provides primitive operators such as map, filter, and concat, as well as more exotic operators for tasks like entering and exiting loops (enter and leave), and generic operators whose implementations can be supplied using closures (unary and binary). It is used to create dataflow programs that can be executed in a distributed manner.