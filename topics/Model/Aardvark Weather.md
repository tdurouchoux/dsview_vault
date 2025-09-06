---
type: Model
---

Aardvark Weather is a deep learning model designed for end-to-end data-driven weather prediction. It replaces the traditional numerical weather prediction (NWP) pipeline with a neural network-based system. The model ingests observational data and produces global gridded forecasts and local station forecasts. It consists of three modules: an encoder module that estimates the initial state of the atmosphere, a processor module that generates forecasts at future lead times, and a decoder module that produces local predictions. Aardvark Weather is trained using high-quality reanalysis data and observational data, and it can be fine-tuned for specific variables and regions to improve accuracy.