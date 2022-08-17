---
audience:
- Introductory and overview
tags:
- Composable
- Ecto
- Query
- Fighting technical debt
title: Better Data Access with Composable Queries
speakers:
- _participants/andrew-ek.md

---
The Ecto.Query DSL gives us a wonderfully expressive tool for fetching data. With a little bit of extra magic, we can create composable, human-readable, expressive, pipeline-able methods that reveal the human meaning behind the data we're accessing, rather than the implementation details of the DB schema itself.  
  
In this talk, I'll show how to begin decomposing existing queries (and creating new queries) with composable queries, how to organize those queries, and how to make them discoverable. I'll also show how to accomplish common joins, make use of subqueries, and other common SQL operations.

AUDIENCE

This talk is best suited for folks who've worked on a big enough codebase (using Ecto) that they've run into the problem of "Wow, this is a big SQL statement, and it's a little bit opaque in meaning!"