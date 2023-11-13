---
audience:
- Intermediate
tags:
- Edge
- Cloud
- Devices
title: The BEAM in Homes across the US. Deploying Nerves at Scale
speakers:
- _participants/frank-hunleth.md
published: true

---
This talk is about lessons, unexpected benefits, and areas for improvement from deploying Elixir and Erlang/OTP on custom hardware running Nerves at SmartRent. SmartRent provides smart home features to rental properties and uses Nerves in smart thermostats and IoT gateways. While we create our own custom hardware and use many Nerves features, this talk is less about that and more about how we’ve ended up using the BEAM. In many ways, it’s a reflection on why we chose the platform in the first place.

The talk starts with describing the types of devices we build and constraints we have with our embedded processors and our deployment environment. OTP comes to the rescue with solutions, and as countless others have, we’ve had a journey of discovery of functionality that we had in the beginning.

Even if you’re not an embedded developer, my hope is that you’ll gain appreciation and insights into developing applications on the BEAM based on our experiences at SmartRent.

**OBJECTIVES:**
This talk aims is to show how we use Erlang/OTP to create resilient devices that can be maintained remotely while in a fairly constrained environment.

**AUDIENCE:**
* Embedded developers using the BEAM
* Elixir and Erlang developers interested in OTP use in a different domain
