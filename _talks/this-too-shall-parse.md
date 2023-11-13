---
audience:
- Advanced
tags:
- Fightning-technical-debt
title: This Too Shall Parse.
speakers:
- _participants/adam-lancaster.md
published: true

---
XML is still a widely used data format and parsing it quickly and efficiently is crucial in certain domains. This is a wild ride through a project my team undertook to improve XML parsing in Elixir for large payloads by 10x.

The approach taken marries a few different ideas but also introduces a parsing approach that slims down the amount of parsing that needs to happen by ignoring data that has not been previously specified as expected. This has good consequences for security as well as performance as I will outline.

Afterwards I extend the idea to JSON parsing with interesting consequences.

**OBJECTIVES:**
I wish to outline a novel parsing technique that helps us reduce the memory footprint of parsing by only parsing the parts of the response that we actually expect to see.

This is a direct application of the common advice to ""parse don't validate"" but does so in a way that actually improves performance. Doing this in a functional language with an event based parser is not trivial so it could add some value to share the considerations that matter.

I also want to discuss the security implications of that approach and pros and cons in general of only parsing the things you expect to receive over the wire.

**AUDIENCE:**
Really anyone who knows some Elixir and who has ever used XML or JSON. It will be even more useful if you have ever had to parse large responses quickly and cheaply.
