[Anil Wadghule](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/858/thumbnail/Anil_Wadghule.jpg?1513601543)

Consultant, Architect & exploring Distributed Systems

#### Building videochat with Elixir and Phoenix

This talk will be my experience report about how I built a videochat system with Elixir and Phoenix.

My app makes use of following features of Elixir and Phoenix:

**\- Realtime with Phoenix channels**

How a Videochat benefits with realtime features of Phoenix frameowkr. In a videochat app, there are are so many interactions which happens in a group, so you need realtime capabilities in your server.

**\- Supervisors**

Instead of crashing, how we gracefully stop services. When users close tabs, other users in videochat should be gracefully informed that user's have quit. I will cover, how we make use of supervisors and gensevers for use cases

**\- Genstage**

For events processing with remote WebRTC media server Third party media server has API and continually sends different events such as network is slow, user's video is unpublished or audio gone off etc. We will see how I make use of genstage's event handling to interactively show user's feedback

**\- Debugging**

We will see how Erlang's debugging tools come in handy when there is something wrong.

[Slides](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/867/original/Anil_Wadghule_-_Building_Videochat_with_Elixir.pdf?1524056998)

[Video](https://youtu.be/-n5IlXBOaBE)

Anil was a long time Ruby developer, then turned Polyglot developer to do Node.js, Java, Scala . For last 1 year, he is writing a Elixir Phoenix web application to build a team communication product. This product involves WebRTC and chat taking full benefit of BEAM's way of concurrency and OTP abstractions.  
  
Anil loves to listen world music. He is an avid reader. Anil is interested in solving problems with better software architectures and learning distributed systems.

Github: [anildigital](https://github.com/anildigital)

Twitter: [@anildigital](https://twitter.com/anildigital)

