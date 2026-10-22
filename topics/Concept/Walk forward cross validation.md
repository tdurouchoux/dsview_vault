---
type: Concept
---

Walk-forward cross-validation is a time-series evaluation technique where the model is trained on a rolling window of historical data and tested on subsequent data points, with the window expanding over time. This method ensures that the model is evaluated on unseen future data, mimicking real-world deployment conditions. SCARLET uses this approach across five expanding windows to validate its forecast engine.