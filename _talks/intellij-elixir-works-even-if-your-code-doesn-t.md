---
audience:
- beginner
- intermediate
- proficient
tags: []
title: IntelliJ Elixir works even if your code doesn't
speakers:
- _participants/elle-imhoff.md

---
IntelliJ Elixir is the Elixir plugin for JetBrains IDEs. It is built around the assumption that your editor should work even your code doesn't compile. By statically analyzing code using its own parser, it is able to resolve and complete code in broken files. Go To Definition and Find Usages show paths through uses, imports, and macros that are thrown out by the Elixir compiler, which allows you to understand macro heavy code. Heuristics find definitions in DSL for Phoenix and Ecto and quote blocks.

  
**Talk objectives:**

* Developers will learn how IntelliJ Elixir can be used to understand their code easier and faster even in the face of errors or gnarly macros.

**Target audience:**

* Developers looking for a richer editor/IDE experience or struggling with complex code bases. Anyone that wants to see how source becomes .beams or macros inject code.