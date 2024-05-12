---
date: 2023-07-28
tags:
  - mathematics
alias: 
---
up:: [[Linear Transformation]]

Given [[Vector Space]]s $U, V$ with [[Hamel Basis]] $B_U \equiv \{u_i\}_{i=1}^n \subset U, B_V \equiv \{v_i\}_{i=1}^n \subset V$. Then there is a unique linear transformation $T: U \to V$ such that 
$$
\forall u_i \in B_U: T(u_i) = v_i \in B_V
$$
each element in $B_U$ gets mapped to $B_V$.

# Proof
Since $B_U$ is a basis for $U$, then each vector $u \in U$ can be written as a [[Linear Combination]]
$$
u = \sum_i \alpha_i u_i
$$
If we seek a linear transformation, it must preserve these combinations, as well as the hypothesis that $T(u_i) = v_i$. 

Therefore, define $T:U \to V$ such that
$$
\forall u  = \sum_i \alpha_i u_i \in U: T(u) \overset{def}{=} \sum_i \alpha_i v_i
$$
## $T$ is linear
Having $u, v \in U$ with respective linear combinations $\sum_i \alpha_i u_i, \sum_i \beta_i u_i$, we have that
$$
u + \lambda v = \sum_i (\alpha_i + \lambda \beta_i) u_i
$$
whose image under $T$ is
$$
T(u+\lambda v) = \sum_i (\alpha_i + \lambda \beta_i) v_i = \sum_i \alpha_i v_i + \lambda \sum_i \beta_i v_i = T(u) + \lambda T(v)
$$
## $T$ is unique
Let $S: U \to V$ be a linear transformation which also preserves basis elements $S(u_i) = v_i$.

Let $u = \sum_i \alpha_i u_i \in U$. Then
$$
S(u) = \sum_i \alpha_i S(u_i) = \sum_i \alpha_i v_i \overset{def}{=} T(u)
$$
Thus, $\forall u \in U: T(u) = S(u)$, and thus $T = S$.

# Corollaries
- [[Every vector space with same dimension are isomorphic to each other]]

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.