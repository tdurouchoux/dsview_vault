---
type: Concept
---

NVLink is a high-speed interconnect technology developed by NVIDIA to connect multiple GPUs within a node or across nodes, enabling fast data transfer and communication. NVLink provides significantly higher bandwidth compared to traditional PCIe connections, making it ideal for parallel processing tasks in machine learning and data science. NVLink interconnects are used to create NVLink domains, where multiple GPUs are fully connected, allowing for efficient collective operations like AllGather and AllReduce. The bandwidth and topology of NVLink connections vary by GPU model and system configuration, with higher-end models like the NVIDIA H100 and B200 offering more advanced NVLink capabilities.