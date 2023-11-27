---
audience:
- Intermediate
tags:
- Edge
- Cloud
- Devices
title: High throughput data conversion for database virtualization
speakers:
- _participants/gourab-mitra.md
- _participants/matthew-pope.md
published: true

---
Hyper-Q is a database virtualization application written in Erlang. It emulates the syntax and semantics of a guest database over a host database, which involves cross-compiling SQL from one dialect to another. Additionally, it emulates functionalities that are not offered by the host database. Tuning Hyper-Q for new SQL workloads involves identifying bottlenecks in the cross-compilation process. This presentation will provide an overview of the diagnosis process for identifying bottlenecks through profiling and will also focus on some architectural changes made to address them.

The main objective of this initiative was to reduce memory consumption during processing, thereby improving the throughput of queries that can be processed through Hyper-Q. This, in turn, assists customers in transitioning from legacy data warehouses to cloud databases with minimum need for application rewrites saving time and effort.

**OBJECTIVES:**
This talk will demonstrate the use of profiling tools, diagnostic process and provide an overview of system architecture at Datometry.

**AUDIENCE:**
Distributed systems developers, architects, Database internals and big data processing enthusiasts.
