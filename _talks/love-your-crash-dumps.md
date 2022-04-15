---
audience:
- intermediate
- advanced
tags:
- BEAM
- performance
- analysis
title: Love Your Crash Dumps
speakers:
- _participants/michal-slaski.md

---
Livebook enabled a new level of interactivity with a running BEAM VM. In this talk we first describe techniques for live analysis of the VM performance, e.g. memory allocation, garbage collection or function call times. We then argue that a controlled termination of a VM, which is in an interesting state, might be a great source of performance information too. We show techniques to inspect the erl_crash.dump file. After this talk you will love your crash dumps more than ever before!