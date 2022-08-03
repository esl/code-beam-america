---
audience:
- intermediate
tags:
- BEAM
title: 'Freestanding Erlang: Porting BEAM close to the metal'
speakers:
- _participants/kent-mcleod.md

---
Erlang and Elixir are great languages for programming concurrent and fault-tolerant applications yet they still require BEAM to run them on real-world hardware. BEAM is a complex piece of software that leverages general purpose operating systems to enable concurrent applications to scale to incredible levels.  
  
But what if you want to run Erlang or Elixir without an OS? Modern operating systems such as Linux are large and complex and can be the wrong choice to deploy on for embedded applications that prioritize security and robustness.  
  
What would it take to run the open-source BEAM implementation in a freestanding environment with no external OS services but still presented a partial POSIX system interface? Would this implementation still allow for useful applications? What are the tradeoffs and what features do we need to give up? This talk tries to answer these questions by presenting a recent project that ported BEAM to a freestanding environment for ARMv7 application processors.

OBJECTIVE

Explain how the BEAM virtual machine can be run in a minimal self-hosted process environment without a runtime dependency on a large general-purpose operating system and discuss what tradeoffs are associated with this approach and why you would want to do this when seeking better security and robustness.

AUDIENCE

Embedded systems software developers as well as anyone else interested in understanding or removing various abstraction layers that sit between our high-level software and the physical machines that compute it.