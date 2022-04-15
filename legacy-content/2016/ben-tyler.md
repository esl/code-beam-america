# Ben Tyler

![Ben Tyler](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/062/thumbnail/240xheadshot.png?1459787352)

Infrastructure Developer @ Booking.com

#### Experimenting with Superpowered Web Services: Phoenix on Riak\_Core

Through Erlang, Elixir developers have access to some amazing tools for building resilient distributed systems. riak\_core is one such tool: it provides the framework behind Riak’s high availability KV store. In this talk, I’d like to explore some unconventional architecture by using riak\_core and Phoenix to build fault-tolerant stateful web applications. What happens when the app servers are also the database nodes? Can we avoid some of the traditional pitfalls of stateful servers? Is this a remotely good idea? Let’s take a look!

**Talk objectives **

Objectives (targeting ~40 minutes):

1) Stateless/stateful setups for web applications — what do these words mean? 5 min

2) CAP in brief, consistent hash rings for distributing work: what are the tradeoffs? 5 min

3) riak\_core - what does it do? Paraphrasing Mariano Guerra’s excellent work. 10 min

4) Build a Phoenix application that cohabitates on a riak\_core hash ring. What superpowers do we gain from this? What do we have to watch out for? Can we do cool tricks with load balancing or channels? In-memory databases for super-speedy responses? 15 min

5) Loosely comparable systems in production/prior art (Microsoft Orleans, Facebook Scuba, others) 5 min

**Target audience**

Intermediate+ Elixir programmers, web developers, students of distributed systems.

[Slides](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/084/original/stateful_web_apps_riak_core_phoenix.pdf?1463048717)

[Video](https://youtu.be/sYYOLaJ-VDQ)

Ben works on service discovery, maps of the infrastructure, and human<->system reliability.

In short, elixir -e 'use Bitwise; \[296, 260, 276, 288, 176\] |> Stream.map(fn x -> x |> (&>>>/2).(2) end) |> Enum.take(5) |> IO.puts # JAPH, :)'

Github: [kanatohodets](https://github.com/kanatohodets)

