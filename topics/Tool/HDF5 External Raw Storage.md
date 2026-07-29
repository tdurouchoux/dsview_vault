---
type: Tool
---

HDF5 (Hierarchical Data Format version 5) external raw storage refers to a feature in the HDF5 library that allows data to be stored externally, outside the main HDF5 file. This can be exploited to read arbitrary files on a system by pointing the external storage path to sensitive locations, such as configuration files or environment variables.