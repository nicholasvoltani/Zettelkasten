---
date: " 2024-05-22"
tags:
  - mathematics
aliases:
---

up:: [[040 MOC Complex Systems]]

![[Pasted image 20240522172809.png]]

Multi-layer graphs are basically a collection of different graphs which are also related to each other.

Given a collection of graphs with [[Adjacency Matrix]] $\{A_{ij}^\alpha\}_{\alpha}$, we have that the multi-layer graph composed by them has adjacency matrix
$$
A = \bigoplus\limits_\alpha A_{ij}^\alpha + C
$$
where the $A_{ij}^\alpha$ matrices compose the main blocks of $A$ (i.e. *intra*-layer relations) and $C$ takes care of off-diagonal blocks (i.e. *inter*-layer interactions).

---
### References
- Casas, Alberto Aleta. “**Networks, epidemics and collective behavior: from physics to data science**”. PhD Thesis, Universidad de Zaragoza, 2019. [https://dialnet.unirioja.es/servlet/tesis?codigo=300533](https://dialnet.unirioja.es/servlet/tesis?codigo=300533).