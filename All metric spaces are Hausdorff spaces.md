---
Date: 2023-06-25
Tags: mathematics
---
up:: [[Metric Topology]]

Let $(M, d)$ be a [[Metric Space]], and $x, y \in M$.

Then let their respective [[Open Balls (Metric Spaces)]] $B_r(x), B_r(y)$ both with radius $r = \frac{d(x,y)}{2}$. 

> Note that $B_r(x) \cap B_r(y) = \emptyset$. 
> Proof by absurd:
Let $z \in B_r(x) \cap B_r(y)$. Then $d(x,z) < r$ and $d(z,y) < r$.
Thus, $d(x,y) \leq d(x,z) + d(z,y) < 2r = d(x,y)$, which is absurd.

Thus, since we have found open sets which separate these points, then this space is a [[Hausdorff Space]].
