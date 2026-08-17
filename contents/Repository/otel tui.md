---
already_read: true
link: https://github.com/ymtdzzz/otel-tui
read_priority: 0
relevance: 3
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-08-17'
---

https://github.com/ymtdzzz/otel-tui

## Summary

otel-tui is a terminal-based OpenTelemetry viewer supporting multiple telemetry formats (OpenTelemetry, Zipkin, Prometheus, Datadog) for traces, metrics, and logs visualization.

**Core Features**
- Supports OpenTelemetry (gRPC/HTTP), Zipkin, Prometheus, Datadog, and DogStatsD input formats
- Visualizes traces, spans, topologies, metrics, and logs in a TUI
- Exposes ports: `4317` (OTLP gRPC), `4318` (OTLP HTTP), `9411` (Zipkin), `8126` (Datadog), `8125` (DogStatsD)
- CORS allows localhost browser telemetry

**Installation**
- Homebrew: `brew install ymtdzzz/tap/otel-tui`
- Go: `go install github.com/ymtdzzz/otel-tui@latest`
- Docker: `docker run --rm -it ymtdzzz/otel-tui:latest`
- Nix: `nix develop github:ymtdzzz/otel-tui`
- Prebuilt binaries available on GitHub Releases

**Configuration**
- CLI flags for enabling receivers (`--enable-zipkin`, `--enable-datadog`)
- Customizable ports (`--grpc`, `--http`) and host (`--host`)
- Prometheus target endpoints via `--prom-target`
- JSON file input via `--from-json-file`

**Clipboard Support**
- Requires `xclip`/`xsel` (Linux), native on macOS/Windows

**Roadmap**
- Metrics: Basic charts (Gauge/Sum/Histogram done), ExponentialHistogram/Summary pending
- UI: Improvements, more keybindings
- Performance: Auto-refresh, async chart rendering
- Config: Refresh interval, buffer size

**Contribution**
- Fork, branch, test (`make lint`, `make test`), PR
- Issues/feature requests welcome

## Links

- [otel-desktop-viewer](https://github.com/CtrlSpice/otel-desktop-viewer/tree/main) : A desktop-based OpenTelemetry viewer that serves as the primary inspiration for the otel-tui project. It provides a graphical interface for visualizing OpenTelemetry data, which otel-tui aims to replicate in a terminal-based format.


## Topics

![[topics/Tool/otel tui]]

![[topics/Tool/Zipkin]]

![[topics/Tool/Prometheus]]

![[topics/Tool/Datadog]]

![[topics/Library/gRPC]]

![[topics/Platform/Homebrew]]

![[topics/Platform/Nix]]

![[topics/Concept/OpenTelemetry]]

![[topics/Platform/Docker]]