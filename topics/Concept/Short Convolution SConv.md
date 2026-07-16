---
type: Concept
---

Short convolution (SConv) is a 1D convolution operation applied over hidden states in transformer models. In Inkling, SConv processes the current token along with the previous W-1 hidden states, where W is the sliding window size. This local processing helps the model capture fine-grained patterns in the data while reducing the computational burden on the attention and Mixture-of-Experts modules. SConv is particularly useful for tasks requiring local representation learning, such as image and audio processing.