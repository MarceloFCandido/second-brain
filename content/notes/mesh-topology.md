---
title: "mesh-topology"
tags:
- 
enableToc: false
---

The mesh topology consists of a network where each device is connected to all others, in a shape of a complete graph. As the number of devices in the network gets higher, more connections are needed to build the topology. 

This physical architecture allows for more [fault-tolerance](notes/fault-tolerance.md) and smaller probability for [data-collision](notes/data-collision.md), but also turns this implementation to be very expensive. One option to overcome these problems is to use the partial version of it: choose wisely witch devices should be interconnected and drop the others connections.

Because of its characteristics, it is not a common to use the mesh topology in Local Area Networks (LAN), but it can be found in WANs ([wide-area-network](notes/wide-area-network.md)) in a hybrid form, the [hybrid-mesh-topology](notes/hybrid-mesh-topology.md).

## References

