---
audience:
- Advanced
tags:
- communication
- " protocol"
- " UOT"
title: On the way to achieve autonomous node communication in the Elixir ecosystem
speakers:
- _participants/hideki-takase.md

---
Have you ever felt that finding communication nodes by specifying information such as IP addresses is complicated?  
  
RTPS (Real-Time Publish Subscribe) is a communication protocol. The main advantage is that nodes can acquire autonomy in communication. Without setting up any broker, a node can automatically discover communication partners for publication/subscription only by specifying a topic. Note that the use of RTPS is restricted to the area under the NAT server.  
  
We are working on R&D about "Rclex," a client library for ROS 2 platform. This library has directly integrated the feature of RTPS into Elixir.  
  
This talk will consider how to bring the power of Rclex into Nerves devices. To find out the current status of Rclex, we will provide a way to realize this purpose. In addition, we will share our latest R&D activity to enable RTPS communication in Elixir/Nerves beyond the NAT server. Once achieved, we can apply RTPS to the wide-area distributed system.