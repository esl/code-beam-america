---
audience:
- Intermediate
tags:
- React
- LiveView
- Integration
title: Sprinklings of React in your LiveView
speakers:
- _participants/andrew-ek.md
published: true

---
As happy as we are writing LiveView (very happy), sometimes the right choice is to use a third-party Javascript library. In this talk, we'll look at the particular case of React components when:

* The React component must coexist on a page with our LiveView
* The LiveView has its own state
* The React component has its own state
* They possibly both interact with the server, which may have its own (more global) state, and update in real-time based on server-side events

Specifically, we'll look at how to set it up so that we can work productively with minimal suffering (or accidental state clobbering). We'll also see how the patterns we use for this particular case (both code organization and using Channels/sockets as the primary contact point, rather than Hooks) can be generalized to handle some fairly complex interactions and integrations regardless of whether we're specifically using React or LiveView!

**OBJECTIVES**

The narrow focus of the talk is to give audience members the tools they need for situations like It sure would be nice if I could just bring [some react component] into this LiveVIew page

More broadly, we'll lay out principles for how to build our systems in this way, and then we'll see how the tools we use (for example, making the React component interact with the server over its own Channel/Socket instead of through the LiveView hooks interface) make our solutions incredibly portable.

There'll also be just a bit about Pub/Sub and the broader "event-state reducer" pattern (which we see already in the various handle_info (etc.) callbacks that take an event and then return a data structure containing the new state.

**AUDIENCE**

This talk will be useful for full-stack developers, particularly those who are using or want to use LiveView and have enough complex needs that they need to reach for third party JS libraries.

It's possibly useful to developers who don't or won't use LiveView but who want to go beyond the conventional request/response REST API (or GraphQL) interaction points and toward something more real-time.
