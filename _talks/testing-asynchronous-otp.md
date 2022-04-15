---
audience:
- intermediate
- advanced
tags:
- testing
- asynchronous
- OTP
title: Testing Asynchronous OTP
speakers:
- _participants/andrea-leopardi.md

---
Testing the functional side of Elixir is great. The mix of immutable data, pure functions, and ExUnit make for a streamlined testing experience.  
  
However, when dealing with async code, you're suddenly faced with problems surrounding state, synchronization points, process-to-process communication, and timeouts.  
  
In this talk, we'll highlight such problems and tell you about the techniques we use to address them. We'll focus on OTP constructs since they're the most common way of using concurrency on the BEAM, but the concepts apply to testing asynchronous code in general.