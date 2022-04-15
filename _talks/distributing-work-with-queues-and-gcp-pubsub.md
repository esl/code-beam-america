---
audience:
- intermediate
- proficient
tags: []
title: Distributing Work With Queues and GCP PubSub
speakers:
- _participants/johanna-larsson.md

---
At Duffel we’re trying to create a frictionless and intuitive API for searching for and booking flights. It turns out, that’s not easy. In this talk, I’ll take you behind the scene and share some of the complexity of searching for flight offers and what brought us to the decision to introduce a queue and workers for handling this. You’ll learn about GCP PubSub and Broadway and how these tools allowed us to reduce variance in processing time and provide a better and more reliable service to our customers.

  
**Talk objectives:**

* Share an interesting and relevant scaling problem and how Broadway and GCP PubSub (or another queue service) can be used to mitigate it

**Target audience:**

* People working with Elixir professionally, especially if they have CPU heavy workloads with low latency expectations