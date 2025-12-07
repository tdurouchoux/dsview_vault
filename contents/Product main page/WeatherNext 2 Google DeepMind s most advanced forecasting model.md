---
already_read: true
link: https://blog.google/technology/google-deepmind/weathernext-2/
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Deep_Learning
type: Content
upload_date: '2025-12-07'
---

https://blog.google/technology/google-deepmind/weathernext-2/
## Summary

Google DeepMind and Google Research have introduced WeatherNext 2, an advanced AI weather forecasting model that generates forecasts 8 times faster and with up to 1-hour resolution. This model can predict hundreds of possible weather scenarios in under a minute using a single TPU, outperforming the previous WeatherNext model on 99.9% of variables and lead times. The improved performance is due to a new AI modeling approach called Functional Generative Network (FGN), which injects 'noise' into the model architecture to maintain physically realistic and interconnected forecasts.

WeatherNext 2's data is now available in Earth Engine and BigQuery, with an early access program on Google Cloud’s Vertex AI platform for custom model inference. This technology has been integrated into various Google products, including Search, Gemini, Pixel Weather, and Google Maps Platform’s Weather API, and will soon power weather information in Google Maps.

The model's ability to predict both 'marginals' (individual weather elements) and 'joints' (complex, interconnected systems) makes it highly skillful and useful for identifying large-scale weather patterns and their impacts. Google is committed to advancing this technology and making it available to the global community, with ongoing research to improve models and expand access.
## Links

- [WeatherNext 2 Model Documentation](https://developers.google.com/weathernext) : Developer documentation for WeatherNext 2, providing technical details and usage instructions for integrating the weather forecasting model.
- [WeatherNext 2 Dataset in BigQuery](https://console.cloud.google.com/bigquery/analytics-hub/exchanges/projects/871883017250/locations/us/dataExchanges/weathernext_19397e1bcb7/listings/weathernext_2_19a39fe59dd) : Access WeatherNext 2 forecast data in BigQuery for analysis and integration into applications.
- [WeatherNext 2 Dataset in Earth Engine](https://developers.google.com/earth-engine/datasets/catalog/projects_gcp-public-data-weathernext_assets_weathernext_2_0_0) : Explore and use WeatherNext 2 forecast data in Earth Engine for geospatial analysis.

## Topics

![[topics/Model/WeatherNext]]

![[topics/Concept/Functional Generative Network FGN]]

![[topics/Platform/Vertex AI]]

![[topics/Platform/Google Earth Engine]]

![[topics/Platform/BigQuery]]