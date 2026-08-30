---
already_read: true
link: https://github.com/SigNoz/signoz
read_priority: 0
relevance: 4
source: null
tags:
- DevOps
type: Content
upload_date: '2026-08-30'
---

https://github.com/SigNoz/signoz

## Summary

SigNoz is an open-source, OpenTelemetry-native observability platform that unifies logs, metrics, traces, alerts, and dashboards for debugging production issues.

**Core offering**
- Open-source alternative to DataDog/New Relic with unified observability
- Deployment options: Cloud (30-day free trial, usage-based pricing from $49), Enterprise (BYOC/self-hosted with compliance), Community (self-hosted, Docker/K8s/Linux)
- Single columnar database optimized for high-cardinality, high-volume workloads

**Monitoring capabilities**
- **APM**: Service latency, error rate, throughput, Apdex, endpoints, DB/external calls
- **Log Management**: Ingest/search/aggregate logs with visual query builder, correlate with traces/metrics
- **Metrics & Dashboards**: Custom dashboards via Query Builder, PromQL, or ClickHouse SQL
- **Infrastructure**: Kubernetes clusters, pods, nodes, host-level CPU/memory/disk/network
- **LLM/AI Observability**: Trace LLM apps, RAG pipelines, prompts, tokens, latency, costs
- **Agent-Native**: SigNoz MCP server for telemetry in coding agents; Noz for incident investigation (Cloud-only)
- **Distributed Tracing**: Flamegraphs, waterfalls, span events, trace analytics
- **Trace Funnels**: Analyze request-flow drop-offs and failed transitions
- **Additional**: Exceptions, alerts, external API monitoring, integrations (OpenTelemetry, Prometheus, K8s, cloud providers, SDKs, databases, LLM tools)

**Key differentiators**
- OpenTelemetry-native instrumentation with telemetry ownership
- Correlated signals (logs, traces, metrics, infra) in one tool
- Predictable pricing (no per-host/user-seat/custom-metric fees)
- Enterprise-ready: SOC 2 Type II, HIPAA, RBAC, ingestion controls, custom retention
- Benchmark: 50% lower resource usage vs. Elastic for ingestion; handles high-cardinality labels where Loki fails

**Getting started**
- Cloud: [Managed workspace](https://signoz.io/teams/)
- Self-host: Foundry, Docker, Kubernetes, or Linux
- Instrumentation: OpenTelemetry, Prometheus, SDKs, integrations

## Links

- [SigNoz APM Documentation](https://signoz.io/docs/instrumentation/overview/) : Comprehensive guide on Application Performance Monitoring (APM) with SigNoz, including service latency, error rates, throughput, and distributed tracing.
- [SigNoz Log Management Documentation](https://signoz.io/docs/logs-management/overview/) : Documentation on ingesting, searching, aggregating, and correlating logs with traces and metrics using SigNoz's visual query builder.
- [SigNoz Metrics and Dashboards Documentation](https://signoz.io/docs/metrics-management/overview/) : Guide to building dashboards for application, infrastructure, and custom metrics using Query Builder, PromQL, or ClickHouse SQL in SigNoz.
- [SigNoz Infrastructure Monitoring Documentation](https://signoz.io/docs/infrastructure-monitoring/overview/) : Documentation on monitoring Kubernetes clusters, pods, nodes, workloads, and host-level metrics with SigNoz.
- [SigNoz LLM Observability Documentation](https://signoz.io/docs/llm-observability/) : Guide to tracing LLM apps, RAG pipelines, prompts, tool calls, tokens, latency, and costs alongside application and infrastructure telemetry in SigNoz.


## Topics

![[topics/Platform/SigNoz]]

![[topics/Concept/Observability in AI Systems]]

![[topics/Concept/Distributed Tracing]]

![[topics/Concept/Trace Funnels]]

![[topics/Concept/OpenTelemetry]]

![[topics/Tool/Prometheus]]

![[topics/Platform/Kubernetes]]

![[topics/Concept/Model Context Protocol MCP]]