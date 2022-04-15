---
audience:
- intermediate
- advanced
tags:
- distributed
- BEAM
- testing
title: Going Multi-Node with ExUnit
speakers:
- _participants/devon-estes.md

---
With ExUnit we can easily run tests in parallel, but what if we want to distribute that parallel work across multiple nodes for even faster test runs? In this talk I'm going to walk through the changes we need to make for this to happen, and in the process we'll learn about distribution and clustering and take a dive into the BEAM code server so we can have a lightning fast, easy-to-use, distributed test runner!