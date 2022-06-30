---
title: "hub_and_spoke-topology"
tags:
- 
enableToc: false
---

The hub-and-spoke topology, also knows as star topology, consists of the devices of the network being connected through a central point (which can be a hub, an access point, etc). 

Although it uses more cabling than [bus-topology](notes/bus-topology.md), for example, being more expensive, it allows easier troubleshooting and more [fault-tolerance](notes/fault-tolerance.md), as the devices in the network use separate cables to connect to the central point. Also, it provides more [scalability](notes/scalability.md), as to connect another device to the network it is needed just one more cable. In the other hand, if the central point fails, all the network goes down.

Some more sophisticated implementations of hub-and-spoke topology are: [[point_to_point-link]] and [[wireless-hub_and_spoke-topology]].

# references

---