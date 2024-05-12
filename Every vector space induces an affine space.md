---
date: 2023-07-21
tags:
  - mathematics
alias: Canonically Obtained Affine Space
---
up:: [[Vector Space]]

Let $(V, +, \cdot)$ be a [[Vector Space]]. Then one can define an [[Affine Space]] $(E, V, +)$ in which $E = V$ and $(V, +)$ is its underlying vector space.

Define by the [[Group Action]]
$$
\begin{align*}
\alpha: V \times (V, +) &\to V\\
(p, v) &\mapsto p + v
\end{align*}
$$
Note that it is indeed a group action, since
- $\forall p \in V, p + 0 = p$
- $\forall p \in V, \forall u, v \in (V, +), (p+v) + w = p + (v+w)$

Note that this group action is [[Regular Group Action|Regular]], since for any two points $p, q \in V$, there is a **unique** vector connecting them (namely, $q - v \in (V, +)$, seeing $p, q \in (V,+)$).

Thus, $\left(V, (V,+), +\right)$ is an affine space induced by $(V, +, \cdot)$.
