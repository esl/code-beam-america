---
audience:
- intermediate
tags:
- AI
- scaling
- Python
title: Creating a scalable intent classifier with Elixir, Python and Tensorflow
speakers:
- _participants/arjan-scherpenisse.md

---
Modern NLP (Natural Language Processing) tasks often build upon large, pre-trained language models like BERT. Neural networks that use these tend to take up a lot of memory, which makes it difficult and costly to scale.  
  
In this talk I present the QnA ninja, a classifier service that recognizes text for for example answering FAQs. Elixir is used to coordinate the classification and training of multiple intent classifiers concurrently. It is capable of scaling by using BERT as a feature extractor combined with distributed Elixir to coordinate pools of Python worker processes.