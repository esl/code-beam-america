---
audience:
- intermediate
- advanced
tags:
- opentelemetry
- monitoring
- scaling
title: Monitoring Elixir With OpenTelemetry
speakers:
- _participants/kamil-kowalski.md

---
There are many application performance monitoring products on the market. Most of them use a dedicated library to instrument your application, which reduces software reusability and interoperability. OpenTelemetry defines a standard way of collecting application traces, metrics, and logs, that is vendor- and language-agnostic. Since OpenTelemetry became stable in early 2021, I'd like to review its Elixir support and share my experience with monitoring Elixir applications at scale.