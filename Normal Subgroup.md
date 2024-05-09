---
Date: 2021-08-15
tags:
  - mathematics 
---
up:: [[Subgroup (Mathematics)]]

Given a [[Group (Mathematics)|Group]] $G$ and a [[Subgroup (Mathematics)|Subgroup]] $N \leq G$, $N$ is a normal subgroup (denoted $N \trianglelefteq G$) if
$$
\forall g \in G, \forall n \in N: g^{-1} n g \in N
$$
# Equivalent definition
[[Normal subgroups imply left cosets equal to right cosets]].
This is equivalent to requiring
$$
\forall g \in G, \forall n \in N: ng = gn \iff \forall g \in G: gN = Ng
$$
that is, the [[Coset]] of $N$, $gN$, are equal to its right cosets $Ng$.

# Equivalence to a homomorphism's kernel
Given a [[Group Homomorphism]] $\varphi: G \to G'$, then [[A homomorphism's kernel is a normal subgroup]]. 

The reciprocal is also true: a normal subgroup $N \trianglelefteq G$ induces a homomorphism
$$
\begin{align}
\varphi:&  \, G \to G/N\\
&g \mapsto gN
\end{align}
$$
whose kernel is $\ker \varphi = N$.
