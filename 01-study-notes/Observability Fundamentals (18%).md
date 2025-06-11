## 🔍 1.1 What Is Observability?


Definition:

Observability is the ability to understand a system’s internal state by examining its outputs: logs, metrics, and traces.

It answers:
- What happened? (Logs)
- When and how often? (Metrics)
- Where and how did it flow? (Traces)

OpenTelemetry focuses on these three signals as pillars to enable deep insight.



## 🔧 1.2 Why OpenTelemetry?
- Vendor-neutral standard under CNCF
- Combines tracing, metrics, and logging collection into one unified SDK & Collector pipeline
- Avoids vendor lock-in (integrates with Jaeger, Prometheus, Grafana, New Relic, etc.)
- Supports many languages: Java, Python, Go, .NET, Node.js, etc.



##  🧱 1.3 Signals in Detail
| Signal  | Use for…                    | Key Features                     |
| ------- | --------------------------- | -------------------------------- |
| Logs    | Debugging & discrete events | Structured/unstructured          |
| Metrics | Monitoring over time        | Aggregatable, numeric            |
| Traces  | Performance & dependencies  | Span → Context → Service mapping |



## 🧠 1.4 OTEL Architecture Basics
- SDK: Instruments code (generates signals)

- API: Language-specific standard to create telemetry data

- Collector: Ingests, processes, and exports data

- Backends: Jaeger, Prometheus, Grafana, Datadog, etc.




