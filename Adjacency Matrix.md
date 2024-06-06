---
date: " 2024-05-22"
tags:
  - mathematics
aliases:
---

up:: [[040 MOC Complex Systems]]

![[Pasted image 20240522173352.png]]

Given a graph $G$, one can describe its nodes' interrelations through $G$'s adjacency matrix $A$. 

# Outward-Arrows Convention
I'll focus on the convention 
$$
A_{ij} \equiv A_{i \to j}
$$
that is, $A_{ij}$ refers to an "arrow" *from* $i$ *to* $j$. 

# Properties
- Given this convention above, one can define each node's [[Node Degree]] (for undirected networks), and their [[In Degree]] and [[Out Degree]] (for directed networks)
- The adjacency matrix description of a graph $G$ is equivalent to its description via a [[Laplacian Matrix]] ─ for [[Simple Graph]]s, at least
- For [[Multi-layer graph]]s, the adjacency matrix of the ensemble of graphs is the direct sum of the individual adjacency matrices of the graphs, plus an intra-layer matrix

---
### References
- Casas, Alberto Aleta. “**Networks, epidemics and collective behavior: from physics to data science**”. PhD Thesis, Universidad de Zaragoza, 2019. [https://dialnet.unirioja.es/servlet/tesis?codigo=300533](https://dialnet.unirioja.es/servlet/tesis?codigo=300533).