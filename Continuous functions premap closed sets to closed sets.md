---
date: 2023-07-01
tags:
  - mathematics
---
up:: [[Topologically Continuous Function]]

Let $f: (X, \tau_X) \to (Y, \tau_Y)$ be a continuous function.

Then we know that 
$$
\forall U_Y \in \tau_Y, f^{-1}(U_Y) \in \tau_X \iff \forall U_Y \in \tau_Y, f^{-1}(U_Y) = U_X \in \tau_X
$$
Let $\mathcal{F}(\tau)$ be the set of closed sets associated to the [[topology]] $\tau$. Since [[The preimage of the complement is the complement of the preimage]], we have that (using $F_Y = Y \setminus U_Y \in \mathcal{F}(\tau_Y)$, and $F_X = X \setminus U_X \in \mathcal{F}(\tau_X)$)
$$
f^{-1}(F_Y) = f^{-1}(Y \setminus U_Y) = f^{-1}(Y) \setminus f^{-1}(U_Y) = X \setminus U_X \in \mathcal{F}(\tau_X)
$$
Thus, continuous functions premap closed sets to closed sets.

# Corollaries
This definition is also equivalent to [[The closure of a continuous image of a closure is the closure of the image]]. That is, for all subsets $D \in \mathbb{P}(X)$, we have that $f(\overline{D}) = \overline{f(D)}$.