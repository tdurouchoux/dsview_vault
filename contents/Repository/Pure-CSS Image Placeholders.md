---
already_read: false
link: https://github.com/ascorbic/unpic-placeholder
read_priority: 1
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2023-09-21'
---

https://github.com/ascorbic/unpic-placeholder
## Summary

The GitHub repository "ascorbic/unpic-placeholder" provides a library for generating low-quality image placeholders (LQIP) using pure CSS. It extracts the dominant color from images or utilizes a BlurHash value for rendering placeholders while images load, improving user experience and reducing Largest Contentful Paint (LCP) time.

Key features include:
- **Dominant Color Extraction**: Uses k-means clustering to identify the dominant color from image pixel data, which is best executed server-side.
- **BlurHash Support**: Generates CSS values from a BlurHash string, allowing for placeholders without client-side JavaScript. This can be applied directly to `<img>` tags or used with frameworks.
- **Installation**: The library can be installed via npm with `npm install @unpic/placeholder`.

Functions provided by the library include:
- `getPalette`: Retrieves a color palette from an image.
- `getDominantColor`: Returns the dominant color of an image.
- `blurhashToCssGradientString`: Converts a BlurHash to a CSS gradient string.
- `blurhashToDataUri`: Generates a data URI for a BMP image from a BlurHash.

The library is compatible with modern JavaScript runtimes, including Node and Deno, and is licensed under the MIT license.
## Links

1. [BlurHash](https://blurha.sh) - A small string representation of a placeholder image that can be rendered while the actual image is loading.
2. [k-means clustering algorithm](https://en.wikipedia.org/wiki/K-means_clustering) - A method used to partition data into clusters, which is utilized in the library to extract dominant colors from images.
3. [unpic-img](https://github.com/ascorbic/unpic-img) - A multi-framework responsive image component designed to work with the unpic-placeholder library.
4. [Imgix](https://blog.imgix.com/2021/01/26/blurhash) - A blog post discussing the BlurHash technique and its applications in image loading.
5. [blurhash](https://github.com/woltapp/blurhash/tree/master/TypeScript) - A TypeScript implementation of the BlurHash algorithm for generating placeholders.
## Topics

- [[topics/Library/unpic-placeholder]]
- [[topics/Concept/BlurHash]]
- [[topics/Concept/k-means clustering]]