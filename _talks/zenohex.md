---
audience:
- Intermediate
tags:
- Edge
- Cloud
- Devices
title: Zenohex - an eloquent, scalable and fast communication library for Elixir
speakers:
- _participants/hideki-takase.md
- _participants/shintaro-hosoai.md
- _participants/mitsuhiro-osaki.md
published: true

---
How do you handle communication in complex networks or when communicating with other languages and IoT devices? Elixir offers various Pub/Sub communication libraries, but network configurations may limit their usability, and some require a broker server.

Zenohex is a high-performance Pub/Sub communication library based on Zenoh, implemented in Rust.  Zenoh has broker-based and broker-less Pub/Sub communications, akin to MQTT and DDS, respectively, but with unique features that enable communication across languages, platforms, and devices. Since Zenohex is realized by using Rustler, this talk will also cover how to integrate Rust modules in your Elixir library. Note that our library also provides Rustler-Precompiled binaries, making it easy to use without a Rust.

We will show a demonstration of controlling a mobile robot remotely using Zenohex integrated with ROS (Robot Operating System).

Github: [https://github.com/b5g-ex/zenohex](https://github.com/b5g-ex/zenohex), Hex.pm: [https://hex.pm/packages/zenohex](https://hex.pm/packages/zenohex)

**OBJECTIVES:**
* Discover a more interoperable and user-friendly communication library.
* Learn about libraries that connect Elixir with other languages.
* Introducing methods to utilize Rust libraries from Elixir.

**AUDIENCE:**
* Interested in trying out a new communication library.
* Searching for a communication library in Elixir.
* Looking to interconnect Elixir with various devices running on cloud, IoT, C language, and more.
* Want to learn how to use Rust libraries in Elixir.
