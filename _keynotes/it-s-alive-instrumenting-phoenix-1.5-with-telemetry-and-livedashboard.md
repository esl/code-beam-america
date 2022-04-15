---
audience:
- Intermediate
tags:
- Metrics
- Phoenix
- Telementry
title: 'Telemetry and LiveDashboard: Elixir Ecosystem Superpowers'
speakers:
- _participants/sophie-debenedetto.md

---
Phoenix 1.5 is here and it comes powered up with out-of-the-box instrumentation and visualization thanks to Telemetry and Live Dashboard.

Phoenix now integrates Erlang's Telemetry library to measure and report standard Phoenix, Ecto and Elixir VM Telemetry events as well as any custom events you'd care to emit from your own application. The Live Dashboard library allows us to visualize the metrics, performance and behavior of our app, as described by these events in real-time. These two offerings together empower every Elixir developer to hit observability goals by writing and shipping fully instrumented code with ease.

With the native Telemetry events executed by Phoenix, we can gain visibility into the behavior of our web app--we can measure and report on things like average request times, identify slow endpoints, see when and where errors are spiking and why. The shiny new LiveView telemetry events allow us to gain the same kind of visibility we’re used to seeing for web requests for our WebSocket-powered Live Views! Meanwhile, Ecto events allow us to measure query times, identify slow and expensive queries and more. All of this illustrates just how powerful a tool Telemetry is in our observability tool box.

In this talk, we'll take a tour through Phoenix's new Telemetry offerings and learn how they work together with Live Dashboard. We'll dive under the hood to understand how Live Dashboard leverages Erlang and Elixir's Telemetry libraries to capture and visualize events as metrics and we'll learn how to take advantage of the out-of-the-box Telemetry events emitted by Phoenix and Ecto. There will be an obligatory picture of Frankenstein.