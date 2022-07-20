---
audience:
- Advanced
tags:
- Elixir
- Machine Learning
- Nx
title: Deep Dive in Nx Backends
speakers:
- _participants/paulo-valente.md

---
Elixir's Nx library implements its features through a configurable backend structure, in which inputs are dispatched to their respective implementations at runtime.

In this talk, we're going to review Nx's Backends and how they play with performance and automatic differentiation.

For this, we're going to study how Nx compiles and executes a given code sample and how using defn, Nx's numerical function definitions, can enable Axon (a deep learning library) to work.

**Talk objectives:**

The main objective of this talk is to shed some light in one of the more technical and internal aspects of Elixir's Nx. There are some articles here and there talking about this, but as part of the Nx team I hope to provide some more information about how the library works. This would also be one of the first talks on the subject.

**Target audience:**

Although the talk is mainly about an Elixir library, I think all BEAM users which have an interest in machine learning would be interested in it, especially since it's a direct product of the EEF Machine Learning Working Group. It can also be interesting for people which come from an ML background but don't know much about the BEAM.