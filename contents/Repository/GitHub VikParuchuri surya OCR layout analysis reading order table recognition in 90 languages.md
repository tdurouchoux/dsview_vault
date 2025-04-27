---
already_read: true
link: https://github.com/VikParuchuri/surya
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Data_Engineering
type: Content
upload_date: '2024-10-16'
---

https://github.com/VikParuchuri/surya
## Summary

Surya is an open-source OCR toolkit capable of document processing in over 90 languages, optimizing tasks such as layout analysis, reading order detection, and table recognition. It offers the following key functionalities:

- **OCR Performance**: Benchmarks indicate competitive performance against cloud services, providing line-level text detection, layout analysis (including headers, images, and tables), and reading order detection.
  
- **Commercial Use**: While primarily aimed at research and personal use, certain conditions apply to commercial usage. Organizations under specific revenue and funding thresholds may obtain exemptions.

- **Interactive Features**: Surya includes a user-friendly Streamlit app and supports various input formats like PDFs, images, and Word documents. Users can specify language options and save results in customizable formats.

- **Installation Requirements**: Requires Python 3.10+ and PyTorch. Installation is executed using pip, with automatic downloading of model weights.

- **Components**:
  - **Text Recognition**: Outputs detected text in JSON format, detailing confidence levels and bounding box coordinates.
  - **Layout and Table Analysis**: Provides detailed location data for layout components like tables and cells.
  - **LaTeX OCR**: Extracts LaTeX from cropped images of equations.

- **Performance Optimization**: Tips for batch size adjustments cater to better utilization of CPU/GPU resources, enhancing processing speeds considerably.

- **Troubleshooting Guidance**: Suggestions for improving OCR accuracy include adjusting image resolutions and modifying detection thresholds.

- **Benchmark Results**: Performance evaluations show Surya's superior recognition capabilities and processing times compared to alternatives like Tesseract and Google Cloud Vision.

Surya is positioned as a powerful, extensible tool for document OCR, emphasizing user accessibility and comprehensive multilingual support.
## Links

- [Surya Repository](https://github.com/VikParuchuri/surya) : The main repository for the Surya OCR toolkit, which supports layout analysis, reading order, and table recognition in over 90 languages.
- [DocLayNet Dataset](https://huggingface.co/datasets/vikp/doclaynet_bench) : A dataset for benchmarking document layouts which can be used for training and evaluating OCR models.
- [EfficientViT Model](https://github.com/mit-han-lab/efficientvit) : A model used for semantic segmentation that was utilized in the training of the text detection in Surya.
- [CRAFT Model](https://github.com/clovaai/CRAFT-pytorch) : A scene text detection model implemented in PyTorch, used as a baseline to compare with Surya's text detection capabilities.
- [Transformers Library](https://github.com/huggingface/transformers) : A popular library for natural language processing, which includes components that may be useful for OCR applications.

## Topics

![](topics/Tool/Surya)

![](topics/Concept/Layout%20Analysis)

![](topics/Concept/Table%20Recognition)

![](topics/Model/LaTeX%20OCR)

![](topics/Library/PyTorch)