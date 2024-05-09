---
Date: 2023-07-11
tags:
  - physics
alias: Galilean Structure
---
up:: [[Euclidean Affine Space]]

![[Pasted image 20230711230207.png|200]]

A Galilean Space-time structure consists of:
1. **Event space**: An [[Affine Space]] $A$ over a four-dimensional vector space $V$ over $\mathbb{R}$
2. **Time map**: A linear mapping $t: V \to \mathbb{R}$ which **measures time intervals between parallel displacements**
	1. Given events $P, Q \in A$ for which $t(Q-P) = 0$, then $P$ and $Q$ are said to be [[Simultaneous Events (Galilean)]]
3. **Distance between simultaneous events**: A distance between simultaneous events $P, Q \in A$ can be defined as $\rho(P, Q) = ||Q-P|| = \sqrt{\left<Q-P, Q-P\right>}$. I.e. it uses the [[Vector Space Norm]] over $V$ which is induced by the [[Euclidean Structure]]'s [[Inner Product]]

An affine space with this structure is said to be a [[Galilean Space]]. Transformations which preserve this structure are called [[Galilean Transformation]]s. Transformations which preserve the galilean structure are [[Galilean Isomorphism]]s.

---
### References
- ARNOL'D, Vladimir Igorevich. **Mathematical methods of classical mechanics**. Springer Science & Business Media, 2013.
