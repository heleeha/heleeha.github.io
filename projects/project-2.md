---
layout: project
type: project
image: images/elevator.jpg
title: Multiple elevators
permalink: projects/multiple-elevators
# All dates must be YYYY-MM-DD format!
date: 2021-04-20
labels:
  - Go
  - TCP/UDP
  - GitHub
summary: Programming multiple elevators to cooperate and serve orders using network.
---

<img class="ui medium right floated rounded image" src="../images/welevator.png">

In this project my team programmed multiple elevators by creating software for controlling n elevators working in parallel across m floors. The elevators were supposed to sufficiently sereve orders and work logically. No orders were supposed to be lost. 

I had previously programmed one elevator so the difference in this project was to get the elevators to "talk" to each other and figuring out wich elevator should take each order. We used UDP to sed packets between the different elevator servers. It was also important that the elevators continued serving orders as normal even if some network connections were lost.
