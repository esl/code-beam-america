---
audience:
- Intermediate
tags:
- types
- BEAM
- Runtime
title: Crossing boundaries with Gleam - from functions to runtime
speakers:
- _participants/raul-chouza.md

---
As BEAM programming languages go, Gleam is a rising star that mantains the same capabilities we love from the platform but adds a slightly different route for constructing programs.  
  
Gleam relies on type signatures and a friendly compiler that can very quickly detect some flaws in our logic. In some scenarios it will help with simple casting errors, but in others the type signatures can guide the design of our programs.  
  
In this talk I would like to take a tabletop game and explore its implementation in Gleam, showing some of the bits and building blocks of the language plus different approaches of doing abstraction through types.  
  
More so, once our core logic is defined we can start thinking on how it can be integrated to the BEAM runtime and how crossing this boundary looks like.

OBJECTIVE

Make the Gleam programming language a bit more familiar to the audience; show different ways we can express our domain through types; show how Gleam programs are used in your BEAM application.

AUDIENCE

Attendees interested in knowing more about Gleam; Gleam programmers looking forward to more Gleam.