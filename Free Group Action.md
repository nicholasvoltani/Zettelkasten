---
Date: 2023-07-08
Tags: mathematics
alias: Free
---
up:: [[Group Action]]

![[Free Group Action SO(2) over real plane.excalidraw.svg|400]]

A group action of a [[Group (Mathematics)|Group]] $G$ over a set $X$ is said to be *free* if all non-identity elements of $G$ "push points away" (i.e. only the identity stabilizes points). That is,
$$\forall g \in G: \forall x \in X: g \cdot x = x\implies g = e_G$$

Equivalently, [[A group action is free iff all its stabilizers are trivial]]: only the identity element keeps elements intact, while all others "induce movement" upon $X$.

## Properties
[[Free Group Actions induce a bijection between the group and a point's orbit]], since all group elements map to distinct points in the space. If it weren't the case, i.e. there were $g \neq h \mid g \cdot x = h \cdot x = x$, then there'd be a non-identity element $(g^{-1} h): x \mapsto x$, which has to be the identity if the action is free.