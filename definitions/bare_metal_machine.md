---
title: Bare Metal Machine
status: Completed
category: technology
---
## Bare Metal Machine

### What it is

Bare metal refers to a physical computer, more specifically a server, that has one, and only one, operating system. The distinction is important in modern computing because many, if not most, servers are [virtual machines](https://github.com/cncf/glossary/blob/main/definitions/virtual_machine.md). A physical server is typically a fairly large computer with powerful hardware built-in. Installing an operating system and running applications directly on that physical hardware, without [virtualization](https://github.com/cncf/glossary/blob/main/definitions/virtualization.md), is referred to as running on “bare metal.”

### The problem it addresses

Pairing one operating system with one physical computer is the original pattern of computing. All the resources of the physical computer are available directly to the operating system and with no virtualization layer present, there is no artificial delay in translating operating system instructions to hardware.

### How it helps

By dedicating all compute resources of a computer to a single operating system, you potentially provide the best possible performance to the operating system. If you need to run a workload that must have extremely fast access to hardware resources, bare metal may be the right solution. 

In the context of [cloud native apps](https://github.com/cncf/glossary/blob/main/definitions/cloud_native_apps.md), we generally think of performance in terms of [scaling](https://github.com/cncf/glossary/blob/main/definitions/scalability.md) to a large number of concurrent events, which can be handled by [horizontal scaling](https://github.com/cncf/glossary/blob/main/definitions/horizontal_scaling.md) (adding more machines to your resource pool). But some workloads may require vertical scaling (adding more power to an existing physical machine) and/or an extremely fast physical hardware response in which case bare metal is better suited. Bare metal also allows you to tune the physical hardware and possibly even hardware drivers to help accomplish your task.
