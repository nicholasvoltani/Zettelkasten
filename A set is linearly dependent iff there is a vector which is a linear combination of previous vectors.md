---
Date: 2023-07-27
tags:
  - mathematics
alias: 
---
up:: [[Linear Dependence]]

Let $(V, +, \cdot)$ be a [[Vector Space]], and $S = \{v_1, \dots, v_n\} \subset V$ (out of which no vector is $0$). 

We seek to prove that 
> $S$ is [[Linear Dependence|Linearly Dependent]] $\iff$ there is some index $k$ in $\{2, \dots, n\}$ for which 
>$$
>v_k = \sum\limits_{i=1}^{k-1} \alpha_i v_i
>$$

# Linear dependence implies there is a vector dependent on previous ones
We prove by contrapositive: if for all indexes, $v_k \notin [v_i]_{i=1}^{k-1}$, we seek to prove that $S$ is [[Linear Independence|Linearly Independent]].

Since all vectors are non-null, $\{v_1\}$ will be L.I.. By hypothesis, all subsequent vectors will not be in the [[Spanning Set|Span]] of the previous ones, for which [[The union of a linearly independent set with a vector outside of its span is also linearly independent]]. Thus, we can construct
$$
\{v_1\} \mathrm{L.I.} \implies \{v_1, v_2\} \mathrm{L.I.} \implies \dots \implies S = \{v_1\}_{i=1}^n \mathrm{L.I.}
$$

# If there is a vector dependent on previous ones, the set is linearly dependent
If there is at least one index $k \in \{2, \dots, n\}$ such that $v_k \in [v_i]_{i=1}^{k-1}$, then the set $\{v_1, \dots, v_k\}$ will be [[Linear Dependence|Linearly Dependent]], which means that adding the rest of the vectors will still keep it L.D..[^1]

---
### References
- [Notas sobre Álgebra Linear](https://nicholasvoltani.github.io/2021-12-27-notas-alglin/)

[^1]: Because if $\{v_1, \dots, v_k\}$ is already L.D., we have that $\{v_1, \dots, v_k, \dots\}$ is L.D., since $$
v_k = \sum\limits_{i=1}^{k-1} \alpha_i v_i + \sum\limits_{i\geq k} 0 v_i
$$ 