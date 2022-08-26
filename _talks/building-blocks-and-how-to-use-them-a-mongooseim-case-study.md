---
audience:
- Intermediate
tags:
- Growth
- Erlang
- OpenSource
title: 'Building blocks and how to use them: a MongooseIM case study'
speakers:
- _participants/nelson-vides.md

---
This is a talk about open source and the community, with MongooseIM as its backbone. MongooseIM is Erlang Solutions’ robust, scalable and customisable messaging server, and using it as a “case study”, I want to tell the story of the evolution of a big and old open source project. I’ll start presenting common Erlang design patterns for a server – the supervision trees, the many processes, the NIFs when they are needed, and most importantly, the ways to preserve a big project manageable and continuously evolving.   
  
I also want to present the libraries that branched off from MongooseIM. In the evolution of a big project, often times you find pieces of code that are not an integral part of the business logic but actually can be generalised and reused for projects potentially very different from your own. I want to present what we found and how, what we extracted, and what we prepared for other people to reuse.

OBJECTIVES

To present MongooseIM in three aspects: an Erlang codebase, an Open-Source project, and a messaging backend. To present the libraries that branched off the main project, together with how-tos and whys, that can be reused by other projects. Ideally, to get diverse developers interested in diverse pieces of code they can reuse in their projects and contribute to, and inspire developers to extract from their projects what is generic and find a way for other people to be able to reuse them.

AUDIENCE

Probably developers of all backgrounds and interests.