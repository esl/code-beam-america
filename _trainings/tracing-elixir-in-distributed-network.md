---
event_date: 5 October
experience:
- Intermediate
title: Tracing Elixir in distributed network
trainers:
- _participants/denys-gonchar.md
summary: In this tutorial, Denys Gonchar will show you how to trace Erlang and Elixir
  programs in a distributed network.
name: Tracing Elixir in a Distributed Network
type: ''
published: false

---
Live tracing is an extremely powerful, yet underutilised feature of the BEAM. It comes from the requirement to troubleshoot live systems handling millions of requests without affecting performance and throughput.

In his tutorial, Denys Gonchar will show you how to trace Erlang and Elixir programs in a distributed network. Tracing allows us to understand a running system from the perspective of the VM. We will discover how to utilise this feature to x-ray everything from a single node to a distributed application, monitoring processes, message passing, system resources as well as local and exported functions.

We will discuss how to incorporate tracing into a development workflow and make tracing safe in production.

**EXPERTISE**

Intermediate

**TARGET AUDIENCE**

Software Developers and Support Engineers

**COURSE DURATION**

 6 hours

**PREREQUISITES**

Practical experience of Erlang or Elixir

**OBJECTIVES**

* Understanding of the low level BEAM trace mechanism
* Understand how tracing fits into the development flow
* Learn to use the most popular tracing tools
* Understand how tracing in a distributed cluster works
* Understand the basics of sequential tracing

**COURSE OUTLINE**

The course covers the topics of tracing in the BEAM virtual machine. It is applicable for both Erlang and Elixir as most libraries are the same. The course covers the following tracing libraries:

* Built-in tracer
* dbg
* recon

The course gives practical advice for tracing on a live system let it be a single node or a distributed cluster. We will discuss how tracing can complement logging and monitoring.