---
audience:
- Intermediate
tags:
- OTP
- " Abstraction"
- " Behavior"
title: OTP Process Abstractions with proc_lib
speakers:
- _participants/Mitchell-Hanberg.md

---
Creating your own generic process abstraction can allow developers to focus on their implementation and not worry about boilerplate. Examples of this exist in OTP with \`gen_server\`, in Elixir's Task, and in libraries like Phoenix with Channels.

Using \`proc_lib\`, you can quickly create your own process abstractions that are OTP-compliant: they're able to be supervised, respond to debugging tools like \`sys:get_state/1\`, and have their own custom callbacks (\`handle_foo\`). This is how \`gen_server\` and \`gen_statem\` are implemented.

In this talk, we'll explore all the different features that you've seen in OTP-compliant processes, what we might want in our own, and hypothesize what it takes to build one. We'll take this hypothesis and walk through building an abstraction for making custom language servers using the Language Server Protocol.

In the end, we'll see that in just a few lines of code, we can easily build our own OTP-compliant process abstraction and use it to build a process.

**Talk objectives:**

* Show developers the tools for creating valuable abstractions in their libraries and application code and give them insight into how the builtin tools are written.

**Target audience:**

* Elixir and Erlang developers looking to increase their understanding and proficiency with OTP.