# Bram Verburg

![Bram Verburg](http://s3.amazonaws.com/esl-conf-stg/media/files/000/000/023/thumbnail/Bram_Verburg.jpg?1458661713)

Security advocate, BEAM enthusiast

#### Learn you some 'ssl' for much security!

Erlang/OTP's built-in 'ssl' application forms the basis of many client and server packages. Unfortunately it has quite a few quirks, potentially leading to weak security. This talk highlights the most important client and server settings for 'ssl' sockets, how the defaults have evolved across OTP versions, and how popular libraries build on them. Topics include cipher suite selection, server hostname verification, known certificate issues (wildcard SAN, cross-signed CA), revocation checks, ECDSA servers, and more.

##### Objectives

Learn to apply secure TLS configurations to clients and servers, either directly with the OTP 'ssl' application or through the many libraries that rely on it: Ranch, Cowboy, Plug, Phoenix, httpc, Hackney, HTTPoison, etc.

##### Audience

Anyone building applications that include TLS client or server functionality, directly or through packages, which means just about anyone developing on the BEAM.

Bram is an architect and security advocate with more than 20 years experience delivering complex software platforms to tier-1 telcos around the world, meeting their stringent security and reliability requirements. He has been using Erlang, and later Elixir, since 2010. As a security advocate, he has taken an interest in the security aspects of the Erlang/OTP ecosystem. This focus he has also continued as a blogger (at https://blog.voltone.net/), trainer, speaker, and open source contributor. His latest project is the X509 package, available on Hex.

Github: [voltone](https://github.com/voltone)

Twitter: [@voltonez](https://twitter.com/voltonez)

