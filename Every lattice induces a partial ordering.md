---
date: 2023-08-01
tags:
  - mathematics
alias: 
---
up:: [[Lattice]]

Given a lattice $(X, \land, \lor)$, one can always create a [[Partially Ordered Set|Partial Ordering]] $\leq$ as
$$
x \leq y \iff x = x \land y \iff y = x \lor y
$$
It can be read as a subset ordering: $X \subseteq Y$ if $X$ itself is its intersection with $Y$, and also if $Y$ is itself the union with $X$ (which is already within it).

## Proof
Given $\leq$, prove that it is a partial ordering:
- **Reflexive**: $\forall x \in X: x = x \land x \implies x \leq x$
- **Transitive**: $\forall x, y, z \in X: (x \leq y) \land (y \leq z) \implies x = x \land y = x \land (y \land z) = (x \land y) \land z = x \land z \implies x \leq z$
- **Antisymmetric**: $\forall x, y \in X: (x \leq y) \land (y \leq x) \implies x = x \land y = y \land x = y$

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 02](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap02.pdf)