---
toc: true
comments: false
layout: base
title: Routing/Computing
description: Blog/Hacks
type: plans
courses: { compsci: {week: 2} }
---

# Networking
A network is essentially a bunch of computer or internet devices that are connected with wires so they can communicate

# Redundancy
The concept of redundancy in networking is vital for fault tolerance. Redundancy involves incorporating extra components to mitigate the failure of any part of the system. The Internet utilizes redundancy to ensure fault tolerance, often by establishing multiple paths between connected devices. In case one route fails, data can be rerouted through alternative paths, enabling continuous network functionality even during system failures. Lack of redundancy can lead to issues, as seen in an example where a backend system lacked alternative pathways, resulting in data transfer problems.

# Popcorn Hack #1
The diagram presented outlines a network and prompts consideration for making it fault-tolerant. Strategies for enhancing fault tolerance might involve introducing redundant components, establishing alternative data paths, or implementing failover mechanisms. Analyzing the specific network structure and identifying potential single points of failure would inform the best approaches to enhance fault tolerance.

# What is Computing?
Computing encompasses the use and operation of computers, involving the design and construction of hardware and software systems for diverse purposes. It includes processing, structuring, and managing information, conducting scientific studies, creating intelligent behaviors in computer systems, developing communication and entertainment media, and gathering relevant information for specific purposes.

# College Board Essential Knowledge

- Sequential Computing: Operates by performing tasks one at a time in a specific order. While easy to manage, it can be slow and resource-intensive.

- Parallel Computing: Breaks a program into smaller parts, allowing simultaneous computation. It is faster but poses more management challenges.

- Distributed Computing: Involves multiple devices running a program to increase computing power without excessive resource consumption. Requires a network for task distribution.

- Sequential Computing: Operates on one task at a time, dependent on the preceding task. Execution time is the sum of individual task durations.
Analogous to computing items sequentially on a conveyor belt.

- Parallel Computing: Schedules tasks to run simultaneously on a single computer. Combines sequential and parallel portions. Requires advanced hardware but offers faster execution, scalable performance.

- Distributed Computing: Distributes tasks to other computers to reduce load. Blends sequential and parallel computing.
Relies on a network for task distribution, potentially taking longer based on network latency.

## Popcorn Hack #2: Sequential, Parallel, or Distributed?
For a small business conducting monthly data analysis, sequential computing may be suitable as tasks can be handled one at a time.
Running a web search engine with user requests involves real-time processing, making parallel computing more appropriate for simultaneous task execution.
A high-resolution weather simulation requiring extensive data suggests distributed computing due to the need for multiple sources and potentially distributed tasks.