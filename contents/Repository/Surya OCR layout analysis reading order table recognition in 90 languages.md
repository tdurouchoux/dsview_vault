---
already_read: true
link: https://github.com/VikParuchuri/surya
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Computer_Vision
- Development_tool
type: Content
upload_date: '2024-10-16'
---

https://github.com/VikParuchuri/surya
## Summary

Surya is a document OCR toolkit that offers the following features:

- OCR in 90+ languages with competitive benchmarks against cloud services
- Line-level text detection in any language
- Layout analysis (table, image, header, etc. detection)
- Reading order detection
- Table recognition (detecting rows/columns)
- LaTeX OCR

Key technical points:

- Works on a range of documents, with usage and benchmarks provided
- Hosted API available for PDFs, images, word docs, and powerpoints
- Licensing: Model weights use a modified AI Pubs Open Rail-M license (free for research, personal use, and startups under $2M funding/revenue), and code is GPL
- Installation requires Python 3.10+ and PyTorch
- Interactive app available for testing Surya on images or PDF files
- Performance tips provided for optimizing GPU and CPU usage
- Benchmarks against Tesseract and Google Cloud Vision for OCR, text line detection, layout analysis, reading order, table recognition, and LaTeX OCR
- Training details provided for text detection and recognition models
- Finetuning script available for training Surya OCR on custom data
- Citation information provided for academic use

Key takeaways:

- Surya is a versatile OCR toolkit with support for multiple languages and document types
- It offers competitive performance against established cloud services and open-source tools
- The toolkit is designed to be user-friendly, with an interactive app and detailed documentation
- Surya is open-source and free for research, personal use, and startups, with commercial licensing available
- The toolkit's performance can be further optimized with provided tips and finetuned on custom data.
## Links

- [Surya OCR Toolkit](https://www.datalab.to?utm_source=gh-surya) : The official website for Surya, a document OCR toolkit that supports OCR, layout analysis, reading order detection, and table recognition in over 90 languages.
- [PubLayNet Dataset](https://github.com/ibm-aur-nlp/PubLayNet) : A dataset used for benchmarking layout analysis, containing labeled images of document layouts.
- [DocLayNet Benchmark Dataset](https://huggingface.co/datasets/vikp/doclaynet_bench) : A benchmark dataset for evaluating text line detection performance across a variety of document images.
- [EfficientViT Architecture](https://github.com/mit-han-lab/efficientvit) : The GitHub repository for EfficientViT, a semantic segmentation architecture used in training the text detection model.
- [Donut Model](https://github.com/clovaai/donut) : The GitHub repository for the Donut model, a transformer-based model used in training the text recognition model.

## Topics

![[topics/Tool/Surya]]