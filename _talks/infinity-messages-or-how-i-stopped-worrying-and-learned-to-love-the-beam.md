---
audience:
- Intermediate
tags:
- Messaging
- Oban
- Broadway
- Growth
title: 'Infinity messages, or: How I stopped worrying and learned to love the BEAM'
speakers:
- _participants/meryl-dakin.md

---
This talk is about how our team leveraged the power of Elixir and the Beam to build a high-powered notification system using recursion and processes. We enabled a messaging system to introspect and call itself in order to deliver messages upon messages, putting our confidence in the Beam’s ability to handle concurrency and Elixir libraries to build a stable, powerful new feature on top of our existing infrastructure. We’ll cover how we approached making this build-over-buy decision, the overall architecture of how our own notification engine powers our webhooks, and how we leverage Oban, Broadway, and AWS Kinesis.

OBJECTIVES

* Introduce a case study on messaging systems
* Discuss async message processing and concurrency in the BEAM and Elixir libraries

AUDIENCE

Those interested in messaging systems, Oban and Broadway, and technical decision-making