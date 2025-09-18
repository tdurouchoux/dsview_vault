---
already_read: false
link: https://github.com/ascorbic/unpic-placeholder
read_priority: 1
relevance: 0
source: null
tags:
- Data_Visualization
type: Content
upload_date: '2023-09-21'
---

https://github.com/ascorbic/unpic-placeholder
## Summary

The unpic-placeholder library is a tool for generating low-quality image placeholders (LQIP) using either the dominant color from an image or a BlurHash value. These placeholders improve the appearance of a page while images are loading and can help reduce Largest Contentful Paint (LCP) time. The library works on modern JavaScript runtimes like Deno, Node, and WinterCG edge runtimes.

Key features include:
- Extracting dominant colors using the k-means clustering algorithm.
- Generating CSS gradients or tiny BMP image data URIs from BlurHash values.
- Functions to convert BlurHash values into CSS strings or objects for easy integration with image tags or components.

The library is designed to work without client-side JavaScript, making it compatible with any web framework. It is particularly useful for improving the user experience by providing visual placeholders while images are being loaded. The library is MIT licensed and can be installed via npm.
## Links

- [BlurHash](https://blurha.sh) : BlurHash is a compact representation of a placeholder for an image. It is used to generate low-quality image placeholders (LQIP) that can be displayed while the actual image is loading.
- [K-means clustering](https://en.wikipedia.org/wiki/K-means_clustering) : K-means clustering is a method used for vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean serving as a prototype of the cluster.

## Topics

![[topics/Library/unpic placeholder]]

![[topics/Concept/BlurHash]]

![[topics/Concept/k means clustering]]