---
date: " 2024-05-23"
tags:
  - mathematics
aliases:
---

up:: [[Adjacency Matrix]]

Given a [[Simple Graph]] with adjacency matrix $A$ and a diagonal matrix of [[Node Degree]]s $D$, the Laplacian matrix is defined as
$$
L = D - A
$$

# Properties
Note that, per definition,
$$
\begin{align*}
\sum\limits_{i} L_{ij} &= \sum\limits_{i}D_{ij} - \sum\limits_{i} A_{ij}\\
&= deg(i) - deg(i)\\
&= 0
\end{align*}
$$

Thus, it is equivalent to the adjacency matrix description of the graph $G$, since one can infer its adjacency matrix from the off-diagonal elements, and since the diagonal elements (i.e. node degrees) are equal to the row-wise sum of $L_{i \neq j}$. In other words, it has no more information than the adjacency matrix $A$. Nevertheless, it is useful in some applications.

---
### References
- [Laplacian matrix - Wikipedia](https://en.wikipedia.org/wiki/Laplacian_matrix#Definitions_for_simple_graphs)