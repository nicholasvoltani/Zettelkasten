---
date: 2023-07-26
tags:
  - mathematics
alias: Span
---
up:: [[021a MOC Linear Algebra]]

Given a [[Vector Space]] $(V, +, \cdot)$ over a [[Field (Algebra)|Field]] $\mathbb{K}$, a subset $S \subseteq V$ is called its *spanning set* if all vectors $v \in V$ can be written as a **finite** [[Linear Combination]] of vectors in $S$.

Namely,
$$
\forall v \in V, \exists \{\alpha_i\}_{i=1}^n \subseteq \mathbb{K}^n, \{v_i\}_{i=1}^n \subseteq S \mid v = \sum\limits_{i=1}^n \alpha_i v_i
$$

# Properties
Note that the span of a vector space's subset is a subspace of its vector space.


---
### References
- [Linear span - Wikipedia](https://en.wikipedia.org/wiki/Linear_span)