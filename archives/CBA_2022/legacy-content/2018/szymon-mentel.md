[Szymon Mentel](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/487/thumbnail/Szymon_Mentel.jpg?1473240791)

Senior System Engineer at Erlang Solutions

#### Instrumenting mayhem: functional chaos engineering

Chaos Engineering is the discipline of experimenting on a distributed system in order to build confidence in the system’s capability to withstand turbulent conditions in production (definition by http://principlesofchaos.org).

In this talk we explore the basics of Chaos Engineering. We take a look at an system design that supports conducting chaos experiments and then we dive into some more low level approaches to injecting faults into a system under test.

First we focus on modelling a Chaos Engineering system using a functional language like Elixir. We discuss how chaos experiments and fault injections are mapped in this language. Later on, we look at the techniques to implement chaos orchestration - i.e. how to inject actual faults into a running distributed system. Finally we briefly go over ideas on how to disrupt a running Elixir node. This section explores actual Elixir code that would be injected during a chaos experiment to trigger faults in the node.

The examples in the presentation correspond to a real Chaos Engineering platform that is being developed and used at Erlang Solutions.

[Slides](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/881/original/Szymon_Mentel_-_Instrumenting_Mayhem_Sharable.pdf?1524058657)

[Video](https://youtu.be/ALL7n7FaOf4)

Szymon Mentel works as a senior System Engineer at Erlang Solutions. For the past three years, he has worked on projects related to Software Defined Networking and is involved with system design and development. He teaches both Erlang and Elixir.

Github: [mentels](https://github.com/mentels)

