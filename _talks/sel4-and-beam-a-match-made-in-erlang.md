---
audience:
- Intermediate
tags:
- Security
- Rpbustness
- seL4
- Innovation
title: 'seL4 and BEAM: a match made in Erlang'
speakers:
- _participants/Ihor-kuz.md

---
Erlang and Elixir can be used to develop robust and highly-available embedded applications with effective fault-tolerance, but the BEAM virtual machine still relies on the underlying operating system to provide a security and robustness foundation which can be insufficient when the OS cannot prevent other components from crashing the system.  
  
The seL4 microkernel is a formally verified operating system kernel designed for embedded systems. seL4 provides isolation mechanisms that can prevent errors or attacks from spreading to other components but it expects each component to mange its own error detection and fault recovery.  
  
I will demonstrate how combining the seL4 microkernel and the BEAM provide an exciting opportunity to fill these gaps. I will also describe my experience with building BEAM-based systems on seL4, integrating BEAM and seL4's inter-process communication mechanisms to allow robust communication between Beam apps and native OS components.

OBJECTIVES

Show how the high-availability programming and communication abstractions of the BEAM can be combined with the communication and programming abstractions of a formally verified microkernel to design and build highly secure and robust internet-connected embedded systems.

AUDIENCE

Embedded systems software developers that are interested in designing and building systems with high levels of security and robustness.