---
already_read: true
link: https://www.nature.com/articles/s41586-025-08897-0
read_priority: 0
relevance: 4
source: Data Points
tags:
- Supervised_Learning
- Development_tool
type: Content
upload_date: '2025-03-21'
---

https://www.nature.com/articles/s41586-025-08897-0
## Summary

The article presents Aardvark Weather, an end-to-end data-driven weather prediction system that replaces traditional numerical weather prediction (NWP) pipelines. Key points include:

1. **System Overview**: Aardvark Weather consists of three modules: an encoder, a processor, and a decoder. The encoder estimates the initial atmospheric state from raw observations, the processor produces forecasts at subsequent lead times, and the decoder generates local predictions.

2. **Data Sources**: The system uses various observational data sources, including remote sensing instruments (e.g., scatterometers, microwave and infrared sounders) and in situ observations (e.g., weather stations, radiosondes). It ingests approximately 8% of the observations used by conventional NWP systems.

3. **Performance**: Aardvark Weather outperforms operational NWP baselines like the Integrated Forecasting System (IFS) and the Global Forecast System (GFS) for several variables and lead times. It provides skilful forecasts for up to ten days, competing with post-processed global NWP baselines and state-of-the-art end-to-end forecasting systems.

4. **End-to-End Tuning**: The system can be fine-tuned end-to-end to optimize performance for specific variables and regions, demonstrating improvements in accuracy for 2-m temperature and 10-m wind speed forecasts.

5. **Advantages**: Aardvark Weather is faster and computationally cheaper than traditional NWP systems. It is easier to improve and maintain, and it can be customized for specific regions and variables, making it accessible for areas with limited resources.

6. **Limitations and Future Work**: The current model does not yet run at the resolution of IFS, and further studies are needed to increase grid resolution and produce forecast ensembles. Additional observational modalities and dealing with observation drift are also areas for future improvement.

7. **Potential Impact**: End-to-end data-driven models like Aardvark Weather have significant potential for real-world applications, including reducing computational costs, enabling bespoke models for specific regions, and improving accessibility in developing areas.

The article concludes by envisioning Aardvark Weather as a pioneer for a new generation of end-to-end weather forecasting systems capable of tackling diverse tasks.
## Links

- [A foundation model for the Earth system](https://doi.org/10.1038/s41586-025-09005-y) : This link points to a research article titled 'A foundation model for the Earth system' published in Nature. The article discusses the development of a comprehensive model for understanding and predicting Earth system dynamics, which is highly relevant to the field of data science and environmental modeling.
- [Accurate medium-range global weather forecasting with 3D neural networks](https://doi.org/10.1038/s41586-023-06185-3) : This link points to a research article titled 'Accurate medium-range global weather forecasting with 3D neural networks' published in Nature. The article presents a study on using 3D neural networks for accurate weather forecasting, which is directly related to the content of the provided text.
- [Probabilistic weather forecasting with machine learning](https://doi.org/10.1038/s41586-024-08252-9) : This link points to a research article titled 'Probabilistic weather forecasting with machine learning' published in Nature. The article explores the use of machine learning techniques for probabilistic weather forecasting, which is highly relevant to the content of the provided text.

## Topics

![[topics/Model/Vision Transformer)]]

![[topics/Model/Aardvark Weather)]]

![[topics/Concept/Remote Sensing)]]

![[topics/Concept/Neural Process)]]

![[topics/Concept/Data Assimilation)]]

![[topics/Concept/Machine Learning in Weather Forecasting)]]

![[topics/Concept/End to End Data Driven Weather Prediction)]]