---
already_read: false
link: https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
type: Content
upload_date: '2023-09-21'
---

https://codelabs.developers.google.com/tensorflowjs-transfer-learning-teachable-machine
## Summary

TensorFlow.js is an open-source machine learning library that can run anywhere JavaScript can, including web browsers, servers, IoT devices, desktop apps, and native mobile apps. It supports multiple backends for execution, such as WebGL, Web Assembly, and CPU. Running TensorFlow.js in the web browser offers benefits like privacy, speed, reach, and cost-effectiveness.

Transfer learning involves taking a pre-trained model (base model) and using it on a similar but different domain. It has advantages like reusing learned knowledge, requiring fewer examples, and faster training times. TensorFlow Hub provides base models suitable for transfer learning.

The codelab guides users through building a web app that replicates Google's "Teachable Machine" website. It involves setting up the app, loading a pre-trained MobileNet model, gathering data from a user's webcam, defining a new model head, training the model, and making predictions. The app allows users to recognize custom objects with just a few example images from their webcam.

Key steps include:
1. Setting up the app with HTML, CSS, and JavaScript.
2. Loading the MobileNet model from TensorFlow Hub.
3. Gathering data from the webcam for multiple classes.
4. Defining a new model head using a multi-layer perceptron.
5. Training the model with the gathered data.
6. Making predictions using the trained model.
7. Implementing a reset button to start over.

The codelab concludes with a recap of what was learned and suggestions for further exploration and sharing projects made with TensorFlow.js.
## Links

- [TensorFlow.js Official Website](https://www.tensorflow.org/js) : The official website for TensorFlow.js, providing documentation, tutorials, and resources for using TensorFlow.js in web applications.
- [TensorFlow.js Pre-made Models](https://www.tensorflow.org/js/models) : A collection of pre-made models available for use with TensorFlow.js, including models for image recognition, natural language processing, and more.
- [TensorFlow.js API](https://js.tensorflow.org/api/latest/) : The official API documentation for TensorFlow.js, providing detailed information on the library's functions, classes, and modules.
- [TensorFlow.js Show & Tell](https://blog.tensorflow.org/search?label=TensorFlow.js&max-results=20) : A collection of projects and demos created using TensorFlow.js, showcasing the library's capabilities and inspiring new ideas for web-based machine learning applications.

## Topics

![[topics/Library/TensorFlow js]]

![[topics/Model/MobileNet]]

![[topics/Platform/TensorFlow Hub]]

![[topics/Concept/Transfer Learning]]