---
audience:
- intermediate
tags: []
title: 'Micro-Services and Events: Friends or Foes?'
speakers:
- _participants/roland-tritsch.md

---
In the last 3 years, Community has built a SaaS platform based on a very sophisticated shared-nothing micro-services architecture, that uses an event-bus for state-propagation. In this talk we will review the architecture and design choices that led us to where we are today, the lessons learned on the way and what challenges lie ahead. Right now we have 60 engineers working on the platform (30 backend (Elixir) engineers). We run \~50 services (and counting). We are processing \~1M events/day. Our uptime (thanks to Elixir/OTP) is 99.999%.

  
**Talk objectives:**

* After the talk, the audience will have learned what questions to ask if/when you want to build a large, scalable SaaS platform that needs to deliver on a very specific set of business requirements.

**Target audience:**

* Senior and Principal Sofware Engineers that need to make design decisions every day.