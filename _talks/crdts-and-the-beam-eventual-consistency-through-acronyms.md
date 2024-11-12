---
level:
- Intermediate
tags:
- CRDTs
- Distributed Systems
- Synchronization
title: "CRDTs and the BEAM: Eventual Consistency Through Acronyms"
speakers:
- _participants/kevin-barrett.md
- _participants/sloane-perrault.md
published: true

---
Conflict-free Replicated Datatypes (CRDTs) allow for distributed, p2p-style workflows where users generate data without conflicts. At screen.garden we wrap Yjs, a CRDT, inside a NIF to push business logic down into clients. This pairs surprisingly well with the BEAM, as we can manage those CRDTs inside stateful processes to turn a fundamentally imperative data structure into a functional one. We can also embrace the BEAM's model of "let it crash" by using the conflict-free part of CRDT to rehydrate state within the BEAM without concern for data corruption or incomplete client-server syncs. All of this allows for fine-grained sync between a server and many devices, without conflicts and without fear of downtime.

**OBJECTIVES:**
- This talk will show the value of CRDTs as a format for passing data between BEAM servers and their clients. It will also detail some code-level decisions, such as using Rustler to wrap Yjs' Rust port in a NIF, and aims to show how these decisions are made possible by the BEAM's greater ecosystem. Finally, the talk will encourage audience members to think about their application state as being distributed across their servers _and_ the clients talking to those servers.

**AUDIENCE:**
- Application authors managing large distributed applications with deep client/device integrations. Also datatype nerds.
