---
already_read: true
link: https://github.com/p-hereford/scarlet
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Data_Analysis
type: Content
upload_date: '2026-10-22'
---

https://github.com/p-hereford/scarlet

## Summary

SCARLET is a fraud-pressure intelligence system for JPMorgan that converts fragmented fraud indicators into actionable control signals by analyzing public complaint data and news trends.

**Purpose**
- Operates above transaction-level fraud models to assess rising fraud pressure and recommend control posture.
- Uses industry-wide complaint velocity and news signals (GDELT) as leading indicators to flag upstream fraud campaigns.

**Architecture**
- **Data ingestion**: CFPB complaints (JPM and industry-wide), GDELT news counts, fetched monthly.
- **Feature engineering**: Weekly aggregates (counts, fraud rate, growth, z-score), with industry features lagged to avoid lookahead bias.
- **Forecast engine**: Two-part hurdle model (logistic classifier + ridge regressor) with walk-forward CV; 62% MAE reduction on stress weeks vs. lag-1 baseline.
- **Decision engine**: Classifies weeks into regimes (normal/elevated/stressed) and assigns control postures (monitor/tighten/etc.).
- **Executive brief**: Plain-language output for senior risk audiences.

**Performance**
- MAE on stress weeks: 55 (CV) vs. 143 (lag-1 baseline), with 1.0 recall on stress events.
- Overall MAE higher than rolling mean (acceptable trade-off for better stress-week performance).
- December 2024 event gap (actual: 450, predicted: 116) due to external incident not captured in data.

**Data sources**
- CFPB Consumer Complaint Database (JPM/industry complaints, 2022–2024).
- GDELT Doc 2.0 API (weekly fraud-related article counts).

**Economic impact**
- Scenario-based loss avoided estimates: $250 proxy per complaint, 0–25% reduction scaled to action intensity.

**Scope limits**
- No transaction/customer-level classification; operates on weekly aggregates only.
- No integration with internal systems; designed for institutional control posture decisions.

**Status**
- Core logic complete; pending licensing, documentation, and repository prep.

## Links

- [CFPB Consumer Complaint Database - Bulk Download](https://www.consumerfinance.gov/data-research/consumer-complaints/) : Official bulk download page for the CFPB Consumer Complaint Database, which includes JPMorgan complaints and industry-wide fraud-relevant product complaints. This is the primary data source for SCARLET's complaint data ingestion pipeline.
- [GDELT Doc 2.0 API Documentation](https://www.gdeltproject.org/) : Documentation and access point for the GDELT Doc 2.0 API, which provides weekly article counts related to JPMorgan fraud or Chase scams. This API is used as a secondary news signal in SCARLET to capture media-driven filing behavior.


## Topics

![[topics/Platform/SCARLET]]

![[topics/Tool/CFPB Consumer Complaint Database]]

![[topics/Tool/GDELT]]

![[topics/Model/Hurdle model]]

![[topics/Concept/Walk forward cross validation]]

![[topics/Concept/Regime classification]]

![[topics/Concept/Control posture]]

![[topics/Library/Scikit Learn]]