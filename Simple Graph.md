---
date: " 2024-05-22"
tags:
  - mathematics
aliases:
---

up:: [[040 MOC Complex Systems]]

![[Pasted image 20240522173352.png]]

A simple graph is a double $(V, E)$, where $V$ is a set of nodes, and $E$ is the set of edges between nodes in $V$.

More generally, one can think of $E$ as a subset of $\mathcal{P}(V) \times \mathcal{P}(V)$, that is, edges have sources and targets that are subsets of $V$. 

For the case of simple graphs, all edges are composed of doubles of singleton sets of nodes, i.e. one-to-one relations between nodes. Thus, one can unambiguously define their [[Adjacency Matrix]].

# Other types of graphs
Other types of graphs can have different compositions of elements of $E$, for instance [[Hypergraph]]s, which can encode more complex relationships between nodes, such as one-to-many (e.g. lectures), many-to-one (e.g. protests) and many-to-many (e.g. complex chemical reactions, I guess?) relationships.

---
### References
- Casas, Alberto Aleta. “**Networks, epidemics and collective behavior: from physics to data science**”. PhD Thesis, Universidad de Zaragoza, 2019. [https://dialnet.unirioja.es/servlet/tesis?codigo=300533](https://dialnet.unirioja.es/servlet/tesis?codigo=300533).