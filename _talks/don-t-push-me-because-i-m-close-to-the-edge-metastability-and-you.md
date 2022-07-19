---
audience:
- Introductory and overview
tags:
- Metastable
- Debugging
- Production
title: Don't Push Me Because I'm Close To The Edge - Metastability And You
speakers:
- _participants/Christian-Koch.md

---
Distributed systems have an emergent property of hidden instability which typically require a confluence of triggers and manifest as black-swan crashes.

What does it mean for a system (your app) to be meta-stable? How do you manage metastability, how do you diagnose it, and how do you develop strategies to mitigate the (often) catastrophic failures that result from metastable crashes?

As systems become more distributed and grow in complexity, there is often a tradeoff between speed and stability. Sometimes this tradeoff is explicit, tech debt, but sometimes you aren’t even sure it’s there. And sometimes that tradeoff can spectacularly blow up in your face.

By talking through a long smoldering incident that manifested in several outages of varying severity, this talk will cover what we’re even talking about when we talk about metastability, what steps we took to mitigate the damaging effects, and how we are working to ensure it’s less likely to happen in the future.

**Talk objectives:**

* This talk aims to explain and demonstrate the concept of metastability and metastable failures.

**Target audience:**

* Anyone interested in a medium-depth dive into debugging production systems.