---
audience:
- Intermediate
tags:
- Elixir
- performance
- Web/Cloud
title: Fast IP address matching in Elixir with Radix Trees and persistent_term
speakers:
- _participants/michael-lubas.md

---
When your web server receives a new login request, is it from a real user, or a rented cloud server? You have a list of thousands of IP prefixes, and need a way to compare each incoming conn's remote_ip to that list.  
  
This problem will be used to illustrate several features of Elixir/Erlang. The beginning of the talk will introduce the problem to the audience, and show why the default Elixir data structures are not suitable. Once the radix tree has been covered, we'll move to the problem of thousands of processes needed to access the same data structure in a short period of time.   
  
The talk will cover GenServers, ETS, and the constant pools optimization, and why these are the wrong choice for the problem. Finally, the complete solution will be shown, using persistent_term.

OBJECTIVES

1. Introduce the problem of IP address matching
2. Show why the radix tree is a good choice
3. Compare GenServers, ETS, and persistent_term for this problem

AUDIENCE

Elixir/Erlang programmers