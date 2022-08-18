---
audience:
- Intermediate
tags:
- IIoT
- FA
- SCADA
- Innovation
title: An Elixir application to a small hydropower plant with Nerves machines
speakers:
- _participants/yutaka-kikuchi.md

---
We have been working on developing small hydropower plants in regional areas in Japan. They have two subsystems, one controlling the plant and the other communicating with a management system on the internet. The latter subsystem, we call SCADA, or Supervisory Control And Data Acquisition.  
  
We often use PLCs, or Programmable Logic Controllers, that are industrial computers for the former subsystem. However, PLCs are unsuitable for SCADA because they are too traditional to be a part of a distributed system like SCADA. Therefore we have been trying to use a modern method for it.   
  
This time, we produce our own machine running Nerves, an extension of BeagleBone Green. Also, we made a program in Elixir to communicate the management system in the cloud. This presentation will report the system that Elixir uses in an industrial field. Also, we will discuss the issue in the domain that we should consider.

OBJECTIVES

This presentation will demonstrate that Elixir can be used in industrial applications by showing an actual application of Elixir in a small hydro-power plant. In addition, the presentation will discuss the issues in applying Elixir to further work of Industrial applications.

AUDIENCE

Alchemists who want to introduce Elixir into Industrial applications.