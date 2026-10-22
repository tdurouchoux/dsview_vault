---
type: Model
---

A hurdle model is a two-part statistical model used to analyze data with excess zeros or infrequent events. In SCARLET, the hurdle model consists of a logistic classifier (first stage) that identifies whether a given week is likely to cross a stress threshold, followed by a ridge regressor (second stage) trained only on stress weeks to estimate expected complaint volume conditional on a spike. The final prediction blends outputs from both stages weighted by spike probability, with a fallback to the four-week rolling mean for non-stress weeks.