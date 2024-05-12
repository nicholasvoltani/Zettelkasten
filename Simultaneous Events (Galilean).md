---
date: 2023-07-11
tags:
  - physics
alias: Simultaneous Event
---
up:: [[Galilean Space-time Structure]]

Given a [[Galilean Space-time Structure]], we say that two points in the [[Affine Space]] $A$ ─ $P, Q \in A$─ are **simultaneous** if $t(\vec{PQ})= 0$, where
$$
t: V \to \mathbb{R}
$$
is the **time functional**, a linear map which measures time intervals between events (separated by vectors in $V$).

Since [[Fixing a point in an affine space induces a vector space]], and [[An affine space with a fixed point is isomorphic to its underlying vector space]], then fixing $P \in A$ induces a time functional with respect to $P$:
$$
\begin{align*}
\tilde{t}_P: V &\to \mathbb{R}\\
& \vec{PQ} \mapsto t(\vec{PQ})
\end{align*}
$$
Since [[The dimension of the kernel plus the dimension of the image equals the dimension of the domain]], we know that $\ker \tilde{t}_P$ has dimension $3$: it is the subspace of all points in $A$ which are simultaneous to $P \in A$.

Also, [[A Galilean Space can be partitioned into simultaneity hyperplanes]], since one can create an [[Equivalence Relation]] between events:
$$
\forall P, Q \in A: P \sim Q \iff t(Q-P) = 0 \iff \vec{PQ} \in \ker(t)
$$


---
### References
- ARNOL'D, Vladimir Igorevich. **Mathematical methods of classical mechanics**. Springer Science & Business Media, 2013.
- [Notes on Mathematical Physics for Mathematicians - Daniel Tausk](https://www.ime.usp.br/\~tausk/texts/MathPhysics.pdf)
