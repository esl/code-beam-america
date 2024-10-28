---
experience:
- Intermediate users
event_date: March 5, 2025
type: in-person full-day tutorial
venue: Marines' Memorial Club & Hotel
trainers:
- _participants/britton-broderick.md
title: "Building Data-Driven Workflows in Broadway"
---

In this course we'll use message brokers, like Rabbit and Kafka, via Docker to set up data pipelines on your local machine to introduce Broadway's functionality. We'll show how it's easy to leverage these tools within Broadway to create data pipelines capable of processing tens of thousands of messages per second.

We'll start with a simple producer and consumer, and work through extending it using various producer-consumers. From there we'll experiment with increasing load at various stages, and how the Erlang VM's fault tolerance combines with Broadway's back-pressure to solve load issues. Then, we'll show how you can instrument your pipeline using telemetry to get valuable insights about how it's performing. Finally, we'll introduce the batching capabilities that come baked into Broadway.

By the time you're finished, you'll have implemented your own ETL pipeline, understand how to integrate it with an existing ETL pipeline, and see how easy it is to switch message brokers without changing the underlying implementation.

**Tutorial objectives:**
1. Set up and configure message brokers with Docker
2. Build scalable data pipelines using Broadway
3. Implement producer-consumer patterns
4. Handle load management and back-pressure
5. Instrument pipelines with telemetry
6. Master Broadway's batching capabilities
7. Create and integrate ETL pipelines

**Target audience:**
- Intermediate users looking to build robust data processing pipelines with Broadway.

**Tutorial prerequisites:**
- Docker
- Elixir
- Familiarity with:
  - Broadway
  - RabbitMQ
  - Kafka
  - Redpanda
  - Some Ecto knowledge
