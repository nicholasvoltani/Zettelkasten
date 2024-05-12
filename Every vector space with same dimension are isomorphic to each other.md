---
date: 2023-07-28
tags:
  - mathematics
alias: 
---
up:: [[Vector Space]]

Given $U, V$ vector spaces with same [[Finitely Generated Vector Space Dimension|Dimension]] $\dim U = \dim V = n$, we seek to prove that they are isomorphic.

Since we know that [[There is only one linear transformation which maps between bases of equal size]], there is a [[Linear Transformation]] $T: U \to V$ such that a [[Hamel Basis]] in $U$ is mapped to a basis in $V$.

# $T$ is surjective $\implies$ $T$ is isomorphism
Let $v \in V$, which can be written as the [[Linear Combination]] $v = \sum_i \alpha_i v_i$. 

Per definition of $T$, we have that $v_i = T(u_i)$. Since we have that $\sum_i \alpha_i u_i \equiv u \in U$, we have that $T(u) = v$. Thus, $\forall v \in V: v \in Im T$, and thus $T$ is [[Surjective Function|Surjective]].

Since [[A linear transformation between spaces of equal dimension is injective iff it's surjective iff it's an isomorphism]], we have that $T$ is an [[Vector Space Isomorphism]] between $U$ and $V$.

# Corollaries
- [[Every vector space is isomorphic to the cartesian product of its field]]

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.