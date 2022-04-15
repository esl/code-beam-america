---
audience:
- intermediate
- proficient
tags: []
title: Get Your CRUD Together!
speakers:
- _participants/andrew-ek.md

---
Most web applications, at their heart, are CRUD (Create / Read / Update / Destroy) applications wrapped around a database with some business logic mixed in. In a Ruby on Rails application, for instance, ActiveRecord provides us with a pre-built set of functions for working with our records. In Phoenix applications, we have Ecto, but it's much less opinionated, and developers are left to their own devices. In this talk we present some opinions on how to organize these operations using Boundaries, Repos, and Queries.

  
**Talk objectives:**

* Discuss limitations of "default" approach (a context + relying on the base application repo + lots of Ecto)
* Propose an alternate approach with a dedicated Repo (abstracting Ecto), Queries, and a Boundary
* Show how this approach can also work to provide a consistent enough interface with external services (e.g. a REST API).

**Target audience:**

* This talk will be most useful to developers who have enough experience with CRUD applications that they have run across some of the pain points I discuss.