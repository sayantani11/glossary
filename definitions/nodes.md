---
title: Nodes
status: Completed
category: Concept
---

## Nodes

### What it is

A node is a computer that works in concert with other computers, or nodes, to accomplish a common task. Take your laptop, modem, and printer, for example. They are all connected over your wifi network communicating and collaborating, each representing one node. In [cloud computing](cloud_computing.md), a node can be a physical computer, a virtual computer, referred to as a VM, or even a [container](container.md).


### Problem it Addresses

While an application could (and many do) run on one single machine, there are some risks involved with that. Namely that the failure of the underlying system will disrupt the application. To address this, developers started creating distributed applications where each process runs on its own node. Thus, nodes run apps or processes as part of a group forming a [cluster](cluster.md), or group, of nodes that works together to achieve a common goal.

### How it Helps

A node gives you a distinct unit of compute (memory, CPU, network) that you can assign to a cluster. In a cloud native platform or app a node represents a single unit that can perform work. Ideally, individual nodes are undifferentiated in that any one node of a particular type is indistinguishable from any other node of the same type.

