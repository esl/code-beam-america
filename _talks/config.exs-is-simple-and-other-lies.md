---
audience:
- intermediate
tags: []
title: '"config.exs is simple" and other lies'
speakers:
- _participants/lukasz-niemier.md

---
One of the most intriguing and confusion-inducing points of Elixir development is configuration. We have compile-time configuration, runtime configuration, startup time configuration, release configuration, application environment configuration, etc. In this talk, I will try to make it a little bit clearer what is what and how and when to use given options.

**Talk objectives:**

* Explain to the audience that the configuration in Elixir is a deep hole that can cause a hell of a lot of confusion and how to make sense of it. When and how the configuration is applied, why some configuration values can and some cannot be changed during the application lifetime, how the configuration is stored, and what is the configuration in the first place.

**Target audience:**

* While I would love to make that talk understandable for beginners, because it is them, who have most problems with configuration, it will probably target mostly slightly more proficient users, who are already accustomed to releases and different places where Elixir can be configured.