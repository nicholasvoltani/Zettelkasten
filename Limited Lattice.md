---
Date: 2023-08-01
Tags: mathematics
alias: Limited
---
up:: [[Lattice]]

Given a lattice $(X, \land, \lor)$, we say it is limited if there are elements $1$ and $0$ which act as its global maximum (denoted $1$) and minimum (denoted $0$), respectively.

A lattice is said to have a **unity** $1 \in X$ if
$$\forall x \in X: x \land 1 = x \iff x \lor 1 = x$$
A lattice is said to have a **neutral element** $0 \in X$ if
$$\forall x \in X: x \land 0 = 0 \iff x \lor 0 = x$$
# Examples
Given a set $X$, its powerset $\mathbb{P}(X)$ is a limited lattice, with unity $X$ and neutral element $\emptyset$.

In a [[Boolean Algebra]], $1$ (denoted $\top$) is absolute truth and $0$ (denoted $\perp$) is absolute falsehood.

# Properties
- Given a limited lattice, one can say two elements $x,y \in X$ are **complements** if[^1]
$$(x \land y = 0) \land (x \lor y = 1)$$
This is very similar to the definition of a [[Connected Space|Disconnected Topological Space]].

- When every element of a lattice has at least one complement, it is said to be a [[Complemented Lattice]]. Note that it need not be unique.

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 02](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap02.pdf)

[^1]: Yes, I'm using $\land$ as the logical "and", as well as the join operator.