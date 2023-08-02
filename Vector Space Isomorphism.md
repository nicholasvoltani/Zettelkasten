---
Date: 2023-07-28
Tags: mathematics
alias: Isomorphic
---
up:: [[Linear Transformation]]

A linear transformation $T: U \to V$ is said to be an isomorphism if it is [[Bijective Function|Bijective]].

# Properties
- [[Every vector space with same dimension are isomorphic to each other]]
- [[A linear transformation between spaces of equal dimension is injective iff it's surjective iff it's an isomorphism]]

**A bijective linear transformation already has linear inverse:**
Let $v_1, v_2 \in V$. Then we have that $\exists! u_1, u_2 \in U \mid T(u_i) = v_i$. Thus
$$\begin{align*}
T^{-1}(v_1 + \lambda v_2) &= T^{-1}(T(u_1) + \lambda T(u_2)) \\
&= T^{-1}(T(u_1 + \lambda u_2)) \\
&= u_1 + \lambda u_2 \\
&= T^{-1}(v_1) + \lambda T^{-1}(v_2)
\end{align*}
$$

**Isomorphisms preserve dimension:**
Via the [[Kernel-Image Theorem]], we have that, since [[A linear transformation is injective iff its kernel is trivial]], as well as being [[Surjective Function|Surjective]] ([[Image of Function|Image]] equals codomain), 
$$\dim U = \dim Im T = \dim V$$