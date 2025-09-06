---
already_read: false
link: https://github.com/ascorbic/unpic-placeholder
read_priority: 1
relevance: 0
source: null
tags:
- Computer_Vision
type: Content
upload_date: '2023-09-21'
---

https://github.com/ascorbic/unpic-placeholder
## Summary

The unpic-placeholder library is a tool for generating low-quality image placeholders (LQIP) using either the dominant color from an image or a BlurHash value. These placeholders improve the appearance of a page while images are loading and can help reduce LCP (Largest Contentful Paint) time. The library works on any modern JavaScript runtime, including Deno, Node, and WinterCG edge runtimes.

Key features include:
- Extracting dominant colors using the k-means clustering algorithm.
- Generating CSS gradients or tiny BMP image data URIs from BlurHash values.
- Pre-generating BlurHash values for use as placeholders.

The library provides several functions for working with dominant colors and BlurHash values, such as `getDominantColor`, `getPalette`, and various functions for converting BlurHash values to CSS strings or data URIs. The library is designed to work with any web framework or without client-side JavaScript, making it versatile for different use cases.
## Links

- [BlurHash](https://blurha.sh) : BlurHash is a compact representation of a placeholder for an image. It is used to generate low-quality image placeholders (LQIP) that can be displayed while the actual image is loading.
- [K-means clustering](https://en.wikipedia.org/wiki/K-means_clustering) : K-means clustering is a method used for vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean serving as a prototype of the cluster.

## Topics

![](topics/Library/unpic%20placeholder)

![](topics/Concept/BlurHash)

![](topics/Concept/k%20means%20clustering)