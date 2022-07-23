---
audience: []
tags:
- Security
- BEAM
title: Security Under the BEAM
speakers:
- _participants/Boyd-multerer.md

---
The BEAM VM is a leader in application-level isolation. Isolated code recovers from faults. Isolated processes can process messages asynchronously with very little coordination. Isolated data means garbage collection is fast and simple. We studied these isolation patterns and asked what would an operating system look like that learned from those lessons and was built to be good at running the BEAM? Could isolation patterns be used to provide deep security that runs from the OS up through the BEAM? 

The resounding answer to that question is yes! In this keynote, we will present our findings and show you how to build software that uses trustworthy isolation, so that if problems do occur, they cannot spread to the rest of the system. The combination of formal methods, the seL4 Microkernel and the BEAM is the magic formula to build a new operation system for the next generation of software and device. We are very excited to present, for the first time, the Kry10 Secure Platform.