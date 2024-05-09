---
Date: 2023-07-28
tags:
  - mathematics
alias: 
---
up:: [[Linear Transformation]]

Given an [[Endomorphism]] $T: V \to V$, we seek to prove that it is injective if and only if it is surjective.

By the [[Kernel-Image Theorem]], we have that
$$
\dim V = \dim \ker T + \dim Im T
$$
For clarity, I'll denote $V_D$ the [[vector space]] of $T$'s domain, and $V_{CD}$ the vector space of its codomain.

# Injective $\implies$ Surjective
Since [[A linear transformation is injective iff its kernel is trivial]], we have that
$$
\dim V_D = \dim Im T
$$
But since $V_D = V_{CD}$, we have that $\dim Im T = \dim V_{CD}$, and thus $T$ is [[Surjective Function|Surjective]][^1].

# Surjective $\implies$ Injective
If $T$ is surjective, we have that $\dim Im T = \dim V_{CD} = \dim V_D$, for which we have
$$
\dim \ker T = 0
$$
for which we conclude that $T$ is [[Injective Function|Injective]].

---
### References
- [Notas sobre Álgebra Linear](https://nicholasvoltani.github.io/2021-12-27-notas-alglin/)

[^1]: Since $Im T \subseteq V_{CD}$ as a subspace, if both have the same [[Finitely Generated Vector Space Dimension|Dimension]], then they must be the same space.