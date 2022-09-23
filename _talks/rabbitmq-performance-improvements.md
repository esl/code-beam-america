---
audience:
- Intermediate
tags:
- RabbitMQ
- Messaging
- Performance
title: RabbitMQ Performance Improvements
speakers:
- _participants/David-Ansari.md

---
This talk starts by providing an overview of RabbitMQ's architecture. Michal and David explain how the Erlang Runtime System is leveraged to implement a scalable message broker.

We discuss performance improvements in recent RabbitMQ releases for all queue types: Classic Queues, Quorum Queues, and Streams.
We provide examples of how we spotted and fixed bottlenecks in the broker thanks to new Erlang/OTP features.
Current performance shortcomings are also addressed in the presentation.

The talk concludes with an outlook of RabbitMQ's future direction and what the community can expect from RabbitMQ in 2023.

**Talk objectives:**

* How to profile Erlang applications
* How to design a scalable message broker on top of Erlang/OTP
* Learning about RabbitMQ's design and architecture

**Target audience:**

* Developers using the Erlang/OTP ecosystem
* RabbitMQ users and operators
* Any attendee with an interest in performance topics