---
level:
- Intermediate
tags:
- Tech Debt
- Ecto
- SQL
title: "Hunting SQL Bottlenecks in Large Elixir Codebases: A Tale of ASTs and Metaprogramming"
speakers:
- _participants/bryan-hunt.md
published: true

---
When faced with a massive Elixir codebase generating problematic SQL queries, the traditional approach of grep-and-pray falls short. How do you track down inefficient queries when the SQL doesn't match the Ecto source code? This talk introduces ecto_probe, a tool that leverages Elixir's powerful metaprogramming capabilities to pinpoint the source of suboptimal SQL during compilation.

We'll explore how ecto_probe integrates with your build pipeline to identify the origin of troublesome SQL hotspots, demonstrate practical examples of tracking down performance-killing queries, and discuss why Elixir's metaprogramming makes this solution possible where statically typed languages like Java or C# fall short. Join us for a deep dive into AST manipulation, compile-time tooling, and the elegant solutions that Elixir's design enables.

**OBJECTIVES:**
- Fighting Technical Debt - Improving legacy systems and breaking the monolith.

**AUDIENCE:**
- Elixir developers involved in DB heavy development, particularly when Ecto queries are produced by functional composition or many layers of abstraction.
