---
level:
- Introductory and overview
tags:
- MLOps
- Machine Learning
- Resilience
title: Fault-Tolerant Machine Learning Operations
speakers:
- _participants/chelsea-troy.md
published: true

---
Running machine learning models in production introduces all kinds of interesting questions:

1. How do we build resilient systems when we don't own the compute we run on?
2. How do we make consumer feedback and accurate telemetry first-class concerns for machine learning products?
3. Machine learning maturity models often prescribe training on production data: inputs that could not only break the system but also change it in hard-to-track ways. How can we de-risk this for a production model?
4. Deterministic code should do the same thing every time, but machine learning models often aren't deterministic. How do we gauge whether systems are working when we don't know exactly what output to expect from the working system?

This talk will explore those questions and outline some solutions for teams to consider. You'll see diagrams and possibly some example code, but the concepts remain language-agnostic and applicable to any ML stack.