---
audience:
- Introductory and overview
tags:
- Containersisation
- DevOps
title: Designing maintainable infrastructure-as-code
speakers:
- _participants/cory-odaniel.md
published: true

---
This talk will focus on designing infrastructure-as-code modules that are maintainable and extensible.

We'll cover important topics like:
* all module registries are a dumpster fire
* handling different lifecycles between related resources
* managing env parity when scale differs
* use-case-specific modules
* designing inputs, outputs, and locals to minimize developer overhead and maximize encapsulating expertise

The talk will use OpenTofu/Terraform to illustrate but applies to other IaC tools like Pulumi and Crossplane.

**OBJECTIVES:**
Introduce developers to writing infrastructure as code that is easy to maintain and extends as their systems evolve.

**AUDIENCE:**
Developers that use cloud services and may or may not have experience with Terraform/Pulumi/OpenTofu
