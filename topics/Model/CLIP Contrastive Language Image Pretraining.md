---
type: Model
---

CLIP is a model developed by OpenAI that learns visual concepts from natural language supervision. It consists of two encoders: a text encoder and an image encoder. The text encoder translates input text into a list of numbers representing each word or token, while the image encoder processes images. CLIP is trained on a dataset of images and their captions, learning to associate images with their corresponding text descriptions. This model is used in Stable Diffusion to translate text information into a numeric representation that can be used by the image generator.