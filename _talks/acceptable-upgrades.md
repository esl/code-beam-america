---
level:
- Intermediate
tags:
- Testing
- Legacy
- Upgrades
title: Acceptable Upgrades
speakers:
- _participants/eric-saxby.md
published: true

---
How do you upgrade a legacy application written around a legacy database—databases designed with best practices from the 90s, with UML looking somewhere between abstract expressionism and piles of spaghetti? …But keep the tests small and understandable, please!

In my experience, people write tests in 3 cases: they’re too stubborn not to; their problems are too complex to solve without them; or their setup is so understandable that there’s no reason _not to._ When working on large untested applications, it’s very easy to skip tests—there’s too much precedent to want to slow down and fight against the current.

Here, I will share patterns and experiments that help to write tests faster—and show that with good tooling you can fight upstream to make it so that you can maintain systems and update them with confidence.

**OBJECTIVES:**
- I would like for more people to test their code, if only because it's frustrating to use websites that crash all the time. Over the past eight years of using Phoenix, LiveView, and Ecto, as well as in building lots of Elixir libraries, I've fought with tests at least as much as I've fought with code. In doing so, I've developed patterns for interacting with Phoenix, Ecto, application config, global state… etc.
- I'd also like more people to contribute to an ecosystem of libraries and patterns to help others test their libraries and applications.

**AUDIENCE:**
Anybody who wants to write better tested code, or who manages projects that they want to be better tested.
