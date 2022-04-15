---
audience:
- intermediate
tags:
- Erlang
- OTP
title: TLS the OTP way
speakers:
- _participants/ingela-andin.md

---
TLS-1.3 is a major upgrade of the TLS-1.2 protocol. A lot of legacy is thrown out and new mechanisms will replace old flawed ones. Most of the TLS handshake will be encrypted as opposed to earlier when most of the first handshake was in plain text and encryption started first when sending the final handshake confirmation message. TLS-1.3 also puts new requirements on TLS-1.2 to pave the way for migration. Supervisors, generic behaviours, logger, gb_trees, ets, queue models, maps, try catch,  
binaries, records how are they used and why.

OBJECTIVE: Spread good design principles with Erlang/OTP and security knowledge by sharing design decisions, trade offs and optimizations that we have done implementing TLS (all versions from SSL 3.0 to TLS 1.3 but with biggest focus on TLS-1.3) in Erlang.

AUDIENCE: People interested in using Erlang/OTP to its full potential, and also people interested in TLS-1.3 in particular and security in general.