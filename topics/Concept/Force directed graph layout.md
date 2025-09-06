---
type: Concept
---

Force-directed graph layout is essentially a physics simulation: you pretend that every node exterts a repulsive force on every other node, and that edges induce an attractive force between the source and target. Typically, the repulsive force decreases quadratically with distance, like a magnet, and the attractive force increases linearly with distance, like a spring. On every tick of the simulation, you compute the net force on every node, and then move each node by its net force vector scaled by some global temperature parameter.