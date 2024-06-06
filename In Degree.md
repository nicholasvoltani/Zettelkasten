---
date: " 2024-05-23"
tags:
  - mathematics
aliases:
---

up:: [[Node Degree]]

![[sink.jpg]]
(Image from [Divergence and Curl « Diet Physics](https://dietphysics.wordpress.com/2010/02/06/divergence-and-curl/))

The in-degree of a node in a graph is the amount of arrows coming **into it**. It is a measure of how many arrows **crash into** a given node.

Using the [[Adjacency Matrix#Outward-Arrows Convention]]
$$
A_{ij} \equiv A_{i \to j}
$$
then the in-degree of a node $i$ is denoted as
$$
deg^-(i) = \sum\limits_{j} A_{ji} \equiv \sumlim_{j} A_{j \to i}
$$
Much care is due to this definition, as it relies entirely on the convention of the Adjacency Matrix $A$.

---
### References
- MATA, A. S. D. Complex Networks: a Mini-review. **Brazilian Journal of Physics**, v. 50, n. 5, p. 658–672, out. 2020.
- [Directed graph - Wikipedia](https://en.wikipedia.org/wiki/Directed_graph#Indegree_and_outdegree)