---
Date: 2023-06-29
Tags: mathematics
---
up:: [[Pseudometric Space]]

Given a [[Pseudometric Space]] $(M, \tilde{d})$, one can create the [[Equivalence Relation]]
$$
x \sim y \iff \tilde{d}(x, y) = 0
$$
Given this relation, we can define the [[Metric Function]]
$$
d([x], [y]) := \tilde{d}(x, y)
$$
for $[x], [y] \in M/\sim$ in the [[Quotient Space]]. 

It is independent on class representatives. Let $x_1, x_2 \in [x], y_1, y_2 \in [y]$. Then
$$
\tilde{d}(x_1, y_1) \leq \tilde{d}(x_1, x_2) + \tilde{d}(x_2, y_2) + \tilde{d}(y_2, y_1) = \tilde{d}(x_2, y_2)
$$
Similarly,
$$
\tilde{d}(x_2, y_2) \leq \tilde{d}(x_2, x_1) + \tilde{d}(x_1, y_1) + \tilde{d}(y_1, y_2) = \tilde{d}(x_1, y_1)
$$
Therefore, $\tilde{d}(x_1, y_1) = \tilde{d}(x_2, y_2)$, and thus $d([x], [y])$ is unambiguous, and $d$ is a metric function on the quotient space $M/\sim$.

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 24](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap24.pdf) 