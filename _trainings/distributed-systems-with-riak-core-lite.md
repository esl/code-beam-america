---
trainers:
- _participants/annette-bieniusa.md
- _participants/mariano-guerra.md
title: Distributed systems with Riak Core Lite
experience:
- Intermediate
summary: This tutorial explores the practical aspects of implementing and testing
  horizontally scalable distributed applications using Elixir with Riak Core Lite.
type: training
published: false

---
This tutorial explores the practical aspects of implementing and testing horizontally scalable distributed applications using Elixir with Riak Core Lite.

Highly-available and scalable systems distribute and replicate data across physically distinct nodes to provide high throughput and fault-tolerance.

While introducing concurrency enables better performance, it requires careful reasoning about consistency of data and computational state to prevent data corruption or loss.

Systems often use techniques like consistent hashing, reader/writer quorums, data versioning and anti-entropy to keep systems consistent and functional, though the tradeoff is additional complexity.

Riak Core Lite is a framework that simplifies the development of dynamo-style architectures, such as highly-available key-value stores, session storage, distributed computation and messaging systems.

**EXPERTISE**

Intermediate

**COURSE DURATION**

1 day

**PREREQUISITES**

Erlang 21 or above, Elixir 1.9/1.10 and Mix installed

**TARGET AUDIENCE**

Elixir developers interested in building scalable services


**OBJECTIVES**

* What are Riak, Riak Core and Riak Core Lite. History and relationship between them
* Properties of the Dynamo Architecture
* What are the main abstractions provided by Riak Core Lite
* What kind of problems are a good fit for Riak Core Lite and the Dynamo Architecture
* Which kinds of consistency are possible with this type of systems
* Alternative libraries, algorithms and data structures available to achieve different consistency levels
* How to setup a Riak Core Lite project using Mix
* How to build, run and test a Riak Core Lite application
* How to build a simple key value store
* How to test it
