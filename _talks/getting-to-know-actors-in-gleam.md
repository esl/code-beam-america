---
audience:
- Intermediate
tags:
- Gleam
title: Getting to know Actors in Gleam
speakers:
- _participants/raul-chouza.md
published: true

---
Gleam is a programming language that makes the case for type safety in the BEAM. Give it a try and you will soon discover that the straightforward syntax and great error messages give you the power to start building your domain logic behind a lovely typed foundation.

It is a great choice for simple finite programs that will not break, but the BEAM offers much more than that... Its process primitive gives us the means to model asynchronous and concurrent work.

Gleam offers a way to represent processes and messages within the type system and uses that to rebuild one of the fundamental abstractions of OTP an Actor. In this talk we’re going to disassemble what makes an Actor and what it takes Gleam to make it work along its type system.

**OBJECTIVES:**
Understand what is a Gleam Actor and how we can map process messages to types.

**AUDIENCE:**
Will briefly go through some of the concepts behind, and Actor and Gleam’s type system, but having familiarity with Erlang’s (or Elixir) GenServer will be useful.
