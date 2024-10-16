---
already_read: true
link: https://github.com/VikParuchuri/surya
read_priority: 3
source: Alpha Signal
tags:
- Computer_Vision
- Natural_Language_Processing
type: Content
upload_date: '2024-10-16'
---

https://github.com/VikParuchuri/surya
## Summary

Surya is an open-source OCR toolkit designed for document processing, supporting over 90 languages. Key features include:

- **OCR Capabilities**: Performs text recognition with line-level detection and benchmarks favorably against cloud services.
- **Layout Analysis**: Identifies document structures such as tables, images, and headers.
- **Reading Order Detection**: Determines the sequence in which text should be read.
- **Table Recognition**: Detects rows and columns in tables.

The toolkit is built on Python and requires PyTorch. It can process various document formats, including PDFs and images, and offers a hosted API for ease of use. Surya is dual-licensed, allowing for free personal use and specific commercial use under certain conditions.

Installation requires Python 3.10+ and can be done via pip. The toolkit includes commands for OCR, layout analysis, reading order, and table recognition, each producing JSON outputs with detailed results.

Performance benchmarks indicate that Surya is competitive with other OCR tools like Tesseract and Google Cloud Vision, particularly in terms of speed and accuracy for text recognition and layout analysis. The toolkit is optimized for GPU usage, with specific batch size settings to enhance performance.

Surya is particularly suited for printed text and may not perform well on handwritten or non-document images. Users are encouraged to preprocess images for better results and can run their own benchmarks to evaluate performance.
## Links

1. [Surya GitHub Repository](https://github.com/VikParuchuri/surya) - A document OCR toolkit that supports layout analysis, reading order, and table recognition in over 90 languages.
2. [EfficientViT](https://github.com/mit-han-lab/efficientvit) - A modified architecture used for semantic segmentation in the training of the Surya OCR model.
3. [CRAFT](https://github.com/clovaai/CRAFT-pytorch) - A scene text detection model that contributes to the text detection capabilities of Surya.
4. [Hugging Face Transformers](https://github.com/huggingface/transformers) - A library that provides state-of-the-art machine learning models, which can be relevant for enhancing OCR capabilities.
5. [PubLayNet](https://github.com/ibm-aur-nlp/PubLayNet) - A dataset used for layout analysis, which is part of the training and evaluation process for the Surya OCR toolkit.
## Topics

- [[topics/Library/Surya]]
- [[topics/Concept/OCR]]
- [[topics/Concept/Layout Analysis]]
- [[topics/Concept/Reading Order Detection]]
- [[topics/Concept/Table Recognition]]