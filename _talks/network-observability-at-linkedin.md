---
audience:
- Intermediate
tags:
- Observability
- Scalability
title: Network Observability at LinkedIn
speakers:
- _participants/anaya-shandilya.md

---
The LinkedIn infrastructure has thousands of services serving millions of requests per second. At this scale, various kinds of data points must be collected, processed and observed to maintain the health of the infrastructure - one of them is network flows.   
  
Our infrastructure components export flows at the rate of 2M packets per second. This talk describes a data collection, processing and storage system for network flow data written in Erlang. It gives an overview of the system’s architecture and some of the interesting challenges we faced while scaling this system.

OBJECTIVE

Share the details about the data processing system we built at LinkedIn using Erlang for collecting and processing high volume and velocity of network flow data

AUDIENCE

Erlang developers / Observability engineers / Backend engineers