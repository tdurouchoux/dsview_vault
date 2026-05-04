---
type: Concept
---

Fixed-point arithmetic is a method of representing real numbers in binary format, where a fixed number of bits is allocated for the integer and fractional parts. In the context of Talos V2, Q4.12 fixed-point math is used throughout the RTL core to represent activations and weights. This format uses 4 bits for the integer part (including the sign) and 12 bits for the fractional part, totaling 16 bits. Fixed-point arithmetic is chosen over floating-point for hardware efficiency, as it reduces resource usage and improves timing closure in FPGA implementations while maintaining sufficient precision for the model's requirements.