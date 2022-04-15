# Andrea Amantini

![Andrea Amantini](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/560/thumbnail/trees.jpg?1487605490)

Distilling Elixir Like an Absolute Beginner at Nextjournal.Com

#### Designing a Multi-Language Live Programming Tool With Phoenix and Genstage

[Nextjournal](https://nextjournal.com) enables living documents for researchers. Our goal is to make technical writing and scientific research easily reproducible and shareable through beautiful typography and live coding tools.  
  
In this talk I'll show how Phoenix channels, [GenStage](https://github.com/elixir-lang/gen_stage) and Erlang ports elegantly solved the complex challenges of building a multi-language, browser-based live programming environment.  
  
Starting with a demo of our editor, this talk will cover:

*   Scheduling of code evaluation using a directed acyclic graph of GenStage nodes: despite a non-standard configuration of stages (mostly of constant demand = 1) I’ll show how to take advantage of GenStage subscriptions to mimic dependencies between code cells.
*   Execution workflows shaped around reactive/functional concepts like observables and signal mapping.
*   Interfacing with foreign languages through erlang ports and having such languages “talk together” with suitable serialisation protocols. Code is executed in user-customisable isolated environments to guarantee reproducibility of the methods used.
*   Using the [transit](https://github.com/cognitect/transit-format) format on phoenix channels and Ecto custom types, for efficiently transferring values between applications

  
Extra topics, time permitting:

*   How we integrated a ClojureScript frontend with Phoenix, building our assets live with [figwheel](https://github.com/bhauman/lein-figwheel)
*   How we implemented real-time collaboration by broadcasting editing operations over Phoenix channels

  
**Target audience:**

*   Although no advanced Erlang/Elixir knowledge is required, we’ll assume some notion of Phoenix channels and a rough idea about GenStage behaviour

**Extras:**

*   [Nextjournal video1](https://esl-conf-static.s3.eu-central-1.amazonaws.com/media/files/000/000/706/original/retake-3-faster.mov?1500364250)
*   [Nextjournal video2](https://esl-conf-static.s3.eu-central-1.amazonaws.com/media/files/000/000/707/original/alanine-retake1.mov?1500364559)

[Slides](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/624/original/ElixirConfEU_2017_-_Designing_a_Multi-Language_Live_Programming_Tool_With_Phoenix_and_Genstage_-_Andrea_Amantini.pdf?1493997531)

[Video](https://youtu.be/p58sFfgMvdI?list=PLWbHc_FXPo2jV6N5XEjbUQe2GkYcRkZdD)

Andrea left academia 6 years ago after a PhD in Algebra and embraced software craftsmanship, inheriting a sense for coherent systems and amalgamation of structures.ty for letting him discover the elegance of the Erlang virtual machine. Andrea contributed with some more or less useful Elixir open source projects including exotic plug adapters, a phoenix OSC controller and some perceptron simulation with OTP. He uses Elixir at work, full-time.

Github: [zampino](https://github.com/zampino)

Twitter: [@lo\_zampino](https://twitter.com/lo_zampino)

