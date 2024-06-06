---
date: " 2024-05-23"
tags:
  - mathematics
aliases:
---

up:: [[040 MOC Complex Systems]]

Given a graph $G$ with [[Adjacency Matrix]] $A$, the degree of a node $i$ is given by
$$
deg(i) = \sumlim_{j} A_{ij}
$$

In the case of an undirected graph, since $A_{ij} = A_{ji}$, the order of the indices does not matter. For directed graphs, on the contrary, one has to distinguish between [[In Degree]]s and [[Out Degree]]s; then, much care is needed on the Adjacency Matrix index convention.

---
### References
- Casas, Alberto Aleta. “**Networks, epidemics and collective behavior: from physics to data science**”. 