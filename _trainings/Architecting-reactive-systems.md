---
experience:
- Intermediate
name: Architecting for Reliability and Scalability
type: tutorial
trainers:
- _participants/Francesco-cesarini.md

---
Learn how to architect fault-tolerant, scalable, soft, real-time systems with requirements for high availability.

In this tutorial, we will look at the steps needed to design scalable and resilient systems. The lessons learnt apply to the Erlang ecosystem, Elixir included, but are in fact technology agnostic and could be applied to most stacks, including Scala/AKKA, .net and others.

\**  
**CHANNEL**

in person

**EXPERTISE**

Intermediate

**DURATION**

4 hours

**PREREQUISITES**

Software development experience is a must, as is the understanding of data consistency models. Experience or exposure to designing and architecting systems is a benefit, but not a prerequisite.

**COURSE OBJECTIVES**

* Distribution: This section covers how to break up your system into manageable microservices. How do you collect these micro services into nodes, which together form distributed architectural patterns, giving you your end-to-end system? What network connectivity do you use to let them communicate with each other?
* Interfaces and state: This section covers how you define your service interfaces. What data and state do you distribute across your nodes, clusters, and data centers? And if requests fail across nodes, what is your recovery strategy?
* Availability: You need at least two computers to make a fault-tolerant system. When dealing with fault tolerance, you have to make decisions about resilience and reliability. This section covers techniques needed to make sure your system never fails and the trade-offs you need to make in your design.
* Scalability: When you picked your distributed pattern, decided how to distribute your data, and made choices on fault tolerance, resilience, and reliability, you also made trade-offs on scalability. This section covers the decisions you have to make and how they affect scalability, as well as how to deal with capacity planning, load regulation, and back pressure.

  The tutorial is based on the last four chapters of Designing for Scalability with Erlang/OTP by Francesco Cesarini. It covers the theory described in those chapters, and whilst interactive, is not a hands-on tutorial.