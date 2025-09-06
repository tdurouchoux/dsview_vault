---
type: Concept
---

GraphTensor is a composite tensor type within TensorFlow that represents both the graph structure and its features attached to nodes, edges, and the graph as a whole. It is accepted as a first-class citizen in tf.data.Dataset and tf.function, allowing for the seamless integration of graph data into TensorFlow workflows. Trainable transformations of GraphTensors can be defined as Layers objects in the Keras API or using the tfgnn.GraphTensor primitive.