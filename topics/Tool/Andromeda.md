---
type: Tool
---

A multithreaded engine for force-directed graph layout in Zig, made a GUI using GTK4 and OpenGL, and named it Andromeda. It is largely inspired by Gephi and the ForceAtlas2 paper. The authors are keen to emphasize the importance of interactivity for working with large scale graph visualization - you need to be able to watch the graph evolving, and dynamically adjust the simulation parameters. You just don't get good results if your tools are opaque and have long iteration times.