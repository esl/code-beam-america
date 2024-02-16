---
audience:
- Intermediate
title: RAFT for database consensus at scale
tags:
- Erlang,
- concurrency,
- databases,
- distributed systems
speakers:
- _participants/henry-sun.md
published: true

---
One of the most difficult problems in distributed computing is consensus, getting participants to a distributed computation to agree. RAFT is a distributed consensus algorithm built around the simple property that no group can simultaneously have two simple majorities.

Join me in learning about RAFT, how it can be used to build databases, and the decision decisions we made when scaling WARaft, WhatsApp's implementation of RAFT in Erlang, to support a message database for 2B+ users.

**OBJECTIVES:**
* Learn what a consensus algorithm is and how a consensus algorithm like RAFT can get a cluster of nodes to agree with each other
* Learn about how we adapted RAFT in WARaft to build a scalable and performant database

**AUDIENCE:**
* Anyone interested in distributed systems or databases
* Basic familiarity with the actor model, state machines and concurrency will help
* Examples will be in Erlang but will not require significant Erlang experience
