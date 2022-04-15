---
speakers:
- _participants/linda-otieno.md
- _participants/sigu-magwa.md
title: Building an emergency software with Phoenix & Elixir
audience:
- Everyone

---
Nailinda is a medical emergency software in Kenya that does not require internet to send and receive messages and emergency request. We use USSD to communicate, capture the request, process it and send the message to the receiver or give a response to the sender - all depends on the content of the message. The receiver is also prompted to give a response, which we capture, process and send back to the initial sender. All this has been built with Phoenix and Elixir, we have used APIs to enable the capturing of the USSD responses.