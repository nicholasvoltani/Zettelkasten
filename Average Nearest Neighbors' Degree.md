---
date: " 2024-05-27"
tags:
  - mathematics
aliases:
---

up:: [[040 MOC Complex Systems]]

![[Pasted image 20240527143845.png]]
Example from [0\_CS7280\_NetworkScience](https://monzersaleh.github.io/GeorgiaTech/CS7280_NetworkScience.html), for $v$'s average nearest neighbors degree, which is $4$: note it takes into account paths from $v$ to itself as well!!!

Given a node $i$ from a graph with [[Adjacency Matrix]] $A$, its average nearest neighbor degree is 
$$
\begin{align*}
k_{i}^{nn} &= \frac{1}{k_{i}}\sum_{j=1}^{N} A_{ij}k_{j} \\
&= \frac{\sum_{j,k} A_{ij}A_{jk}}{\sum_{j}A_{ij}}
\end{align*}
$$
That is, it is the weighted average degree from $i$'s neighbors (weighted by $i$'s row of the adjacency matrix). Do not forget that these degrees also take $i$ into account! In fact, [[A simple graph's node is a (local) star graph center iff its average nearest neighbors degree equals 1]]!

# $k_{nn}$ in terms of powers of the adjacency matrix
One can also see this measure as referring to the second power of the adjacency matrix, i.e. to $2$-paths coming out of $i$:
$$
k_{i}^{nn} = \frac{\sum_{j} (A^{2})_{ij}}{\sum_{j}A_{ij}}
$$

---
### References
- BOCCALETTI, S. et al. Complex networks: Structure and dynamics. **Physics reports**, v. 424, n. 4–5, p. 175–308, 2006.