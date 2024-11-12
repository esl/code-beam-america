---
level:
- Intermediate
tags:
- Code Generation
- Development Tools
- Customization
title: Crafting Fully Custom Code Generators
speakers:
- _participants/jeffrey-matthias.md
- _participants/aidan-obley.md
published: true

---
Phoenix is powerful because it allows you to shape your code to meet your needs and just works. Your code generators should reflect that philosophy as well. Even with the customizable templates provided, there are choices baked into Phoenix's generators that make them often seem like a learning resource but not a tool for speeding up your development.

Learn how straight forward it is to create code generators in an Elixir application that will allow you to specify every aspect of the code, including application architecture, file paths, test style, which packages to leverage, and more.

**OBJECTIVES:**
- give developers something they can implement and leverage right away
- demonstrate the benefits of fully custom code generation
    - encourage consistent patterns in your codebase
    - codify agreed to design and architecture decisions
    - speed up boilerplate
    - avoid copy/paste related issues
    - update/replace generated code in same file as custom logic
    - create schema and factories from existing databases
- distinguish fully custom code generation from modifying the phoenix templates
- simplify the mysteries of fully custom code generation
- show how to turn existing code into a generator
- explore using complex inputs using files instead of the command line
- clarify the relationship between code generation and meta-programming and how to use them together
- mention existing projects that may help make generation more efficient (igniter and sourceror)

**AUDIENCE:**
- Whether working solo or on a team, anyone writing an application who wants to speed up and add consistency to their codebase will benefit from the topics covered.
