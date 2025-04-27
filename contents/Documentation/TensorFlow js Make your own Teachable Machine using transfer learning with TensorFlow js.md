---
already_read: false
link: https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
- Data_Engineering
type: Content
upload_date: '2023-09-21'
---

https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine
## Summary

The codelab provides a practical guide for web developers to create a "Teachable Machine" using TensorFlow.js and transfer learning. Key aspects include:

1. **Introduction to Transfer Learning**: This technique allows leveraging pre-trained models (like MobileNet) to classify new data effectively with fewer examples, benefiting from accelerated training and lower data requirements.

2. **TensorFlow.js Overview**: This library enables machine learning within various JavaScript environments (browsers, Node.js, IoT devices) using multiple backends (WebGL, WebAssembly, CPU) for optimal performance.

3. **Implementation Steps**: Developers are guided to:
   - Set up a web app using HTML, CSS, and JavaScript.
   - Utilize TensorFlow.js to load a pre-trained model (MobileNet) for feature extraction from webcam data.
   - Collect training data dynamically from the webcam for different classes using button controls.
   - Define a simple model architecture (multi-layer perceptron) to categorize new inputs based on the features extracted.
   - Train and predict classifications in real-time.

4. **Functionality**: The codelab includes code for enabling the webcam, gathering data, training the model, making predictions, and resetting the application state to allow for new training sessions.

5. **Key Takeaways**:
   - Transfer learning simplifies training on custom datasets, reducing time and resource use.
   - The resulting application can classify real-time webcam inputs based on user-defined training data.
   - The completed project encourages further experimentation and application to real-world problems, showcasing potential uses of AI in user-specific contexts.

This codelab equips developers with skills to implement machine learning in web applications using JavaScript, promoting creativity and practical applications in various industries.
## Links

- [TensorFlow Hub - Available Models](https://tfhub.dev/s?deployment-format=tfjs) : Explore available TensorFlow models specifically for use with TensorFlow.js.
- [MobileNet V3 on TensorFlow Hub](https://tfhub.dev/s?deployment-format=tfjs&network-architecture=mobilenet-v3) : Find MobileNet V3 models hosted on TensorFlow Hub for image classification and feature extraction.
- [TensorFlow.js Documentation](https://www.tensorflow.org/js) : Official TensorFlow.js documentation covering guides, API references, and tutorials.
- [Understanding One-Hot Encoding in Machine Learning](https://developers.google.com/machine-learning/glossary#one-hot_encoding) : Detailed explanation of one-hot encoding and its importance in machine learning.
- [TensorFlow.js API Reference](https://js.tensorflow.org/api/latest/) : Access the latest API documentation for using TensorFlow.js.

## Topics

![](topics/Library/TensorFlow%20js)

![](topics/Concept/Transfer%20Learning)

![](topics/Platform/Glitch%20com)

![](topics/Model/MobileNet)

![](topics/Concept/Web%20based%20Machine%20Learning)

![](topics/Concept/Real%20Time%20Prediction)