---
type: Library
---

A library for generating low-quality image placeholders (LQIP) by extracting the dominant color from an image or rendering a BlurHash value. It works on any modern JavaScript runtime, including Deno, Node, and WinterCG edge runtimes. It can render BlurHash to either a set of CSS gradients or a tiny BMP image data URI, typically around 150 bytes in size, which can be applied as a background image to an img element.