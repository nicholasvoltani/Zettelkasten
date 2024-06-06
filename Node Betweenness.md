---
date: " 2024-05-27"
tags:
  - mathematics
aliases:
---

up:: [[040 MOC Complex Systems]]

![[Example-Betweenness-Centrality-scores-for-a-small-graph.png]]
Example of betwenness for a small graph (unnormalized).  Source: [Example Betweenness Centrality scores for a small graph  | Download Scientific Diagram](https://www.researchgate.net/figure/Example-Betweenness-Centrality-scores-for-a-small-graph_fig1_282990849)

> "A point is considered to be central here to the degree that it falls between other points on their shortest or geodesic communication paths. A point falling between two others can facilitate, block, distort or falsify communication between the two; **it can more or less completely control their communication**. But if it falls on some but not all of the geodesics connecting a pair of points, its potential for control is more limited." (Freeman, 1977; my emphasis)

The betweeness of a node $i$ (in a [[Simple Graph]] $G$) is a measure of, given [[Shortest Path Distance]]s between all nodes $j \neq k$, how "likely" it is to have to pass through $i$. It is a measure of $i$'s **centrality**.

It's given by
$$
b_{i} = \frac{2}{(N-1)(N-2)}\sum\limits_{j \neq k} \frac{\# (j \to i \to k)}{\#(j\to k)}
$$

This normalization factor $\frac{(N-1)(N-2)}{2}$ is the amount of possible shortest paths from $j$ to $k$ through $i$ in the maximal case in which $i$ is central: the [[Star Graph]] where $i$ is the central node.

---
### References
- FREEMAN, L. C. A Set of Measures of Centrality Based on Betweenness. **Sociometry**, v. 40, n. 1, p. 35–41, 1977.