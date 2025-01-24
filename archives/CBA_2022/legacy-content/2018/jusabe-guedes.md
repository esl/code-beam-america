[Jusabe	Guedes](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/847/thumbnail/Jusabe_Guedes.jpg?1513360244)

Software Engineer at B2W Digital

#### Orchestrating Consumers and Producers Like an Octopus

Imagine an scenario where an queue needs to be consumed and each element must pass through a pipeline which the result may go to a different bucket. Each bucket must work independently making sure all elements are correctly processed and flushed whenever is possible.

Orchestrating many consumers/producers at the same time can be challenging, specially when the operation depends on third party services which have different constraints. With that in mind we are going to show an use case of how we achieved the parallelism necessary to smoothly work with thousands of clients simultaneously. We'll see how things like GenStage and GenServer can take all the heavy lifting, letting us focus on the business logic.

[Slides](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/872/original/Jusabe_Guedes_-_Orchestrating_Consumers_and_Producers_Like_an_Octopus.pdf?1524057311)

[Video](https://youtu.be/_4ENJB3qkLo)

Jusabe is a Software Engineer who recently discovered Elixir and became passionated about it at the first sight. On his current work he uses mainly Ruby and Elixir to provide solutions for customer's needs. He is type of person that likes to know how things work instead of just using it. After some years consuming content from the community, he decided to start giving back by going out and producing Elixir content(even being a newbie). You can find some blog posts at medium.com/@dojusa.

Github: [dojusa](https://github.com/dojusa)

Twitter: [@dojusa](https://twitter.com/dojusa)

