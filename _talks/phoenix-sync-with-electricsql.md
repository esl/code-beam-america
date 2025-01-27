---
audience:
- Intermediate
tags:
- Phoenix
- LiveView
- Elixir
- Edge, Cloud & Devices
title: Phoenix sync with ElectricSQL
speakers:
- _participants/james-arthur.md
published: true

---
At ElixirConf US in September 2024, José gave a keynote outlining his vision for Phoenix sync. This talk introduces our work implementing Phoenix sync with ElectricSQL, an open source sync engine developed in Elixir that we've adapted under his guidance to realise José's original vision.

The talk re-caps the design objectives of local-first sync into the front-end directly from Phoenix and Ecto. It talks through our implementation approach with Electric and shows you how you can use the new Electric.Phoenix library to add sync to your Phoenix applications.

This includes syncing ""shapes"" based on Ecto queries, for direct sync into the front-end. And it includes syncing into the LiveView client using Phoenix.Streams via a new `electric_stream/2` function.

**OBJECTIVES:**
Update the community on the development of the https://github.com/josevalim/sync project.

Introduce the new https://hexdocs.pm/electric_phoenix library. Show Elixir developers how they can use it. They should come out of the talk with an understanding of how to:

1. add local-first sync to their Phoenix applications, using https://hexdocs.pm/electric_phoenix/Electric.Phoenix.Plug.html
2. add realtime multi-user sync to their LiveView applications using https://hexdocs.pm/electric_phoenix/Electric.Phoenix.LiveView.html#electric_stream/4

**AUDIENCE:**
Phoenix developers. LiveView developers.

Developers working on:
- realtime systems / multi-user sync
- next generation SaaS and AI applications
- data analytics and visualisation
- local-first software

N.b.: it's suitable for all levels:
- easy to understand and usable by beginners
- interesting for intermediate and advanced
