# Claudia Doppioslash

![Claudia Doppioslash](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/461/thumbnail/Claudia_Doppioslash.jpeg?1470253705)

Functional Programmer & Gamedev

#### Building a Graphical IDE in Elm/Purescript for an Embedded Language that Compiles to the Erlang VM

Functional Programming languages that compile to Javascript can be used to develop complex frontend projects successfully, while sparing yourself a lot of pain and obsessive test coverage.

In this deep dive into the Typed-FP-languages-targeting-Javascript ecosystem, I'll show you how we used Elm to build a complex IDE for a visual PLC language for embedded hardware (Programmable Logic Controllers).

Our PLC programming language implementation gets compiled to BEAM files and runs in the Erlang VM.  That allows us to take advantage of Erlang's distributed model, and through our custom websocket library the IDE can talk directly with a Cowboy handler running on the device, to get debugging information in realtime. 

We'll also cover our choice of framework when porting the IDE to Purescript, good and less good parts of the two languages, and how they relate to Haskell.

**Talk objectives:**

*   Get an overview of Elm and Purescript 
*   Experience report after using Elm for a real life complex project with deadlines.
*   Experience report of porting an Elm program to Purescript

**Target audience:**

*   Frontend developers who are tired of Javascript
*   Developers interested in typed Functional languages for the frontend
*   Developers interested in Elm or Purescript

[Slides](http://doppioslash.com/slides/ElixirConf2017.pdf)

[Video](https://youtu.be/ngWo5e-294o?list=PLWbHc_FXPo2jV6N5XEjbUQe2GkYcRkZdD)

Claudia Doppioslash is a Functional Programmer and a gamedev. Having learned many languages, she ended up preferring strongly typed functional languages, though she's still a moderately smug LISP weenie. These days she's exploring what FP can do for industrial control systems front-ends, using Erlang and Elm.

Github: [doppioslash](https://github.com/doppioslash)

Twitter: [@doppioslash](https://twitter.com/doppioslash)

