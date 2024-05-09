---
Date: 2023-07-20
tags:
  - mathematics
alias: The boundary is idempotent iff its interior is empty
---
up:: [[Boundary (Topology)]]

> The boundary has no boundary if it doesn't have any "meat"/"width" (i.e. no interior).

Let $S \subseteq X$ be a subset of a [[Topological Space]] $(X, \tau)$.

Let $\partial S$ be its [[Boundary (Topology)|Boundary]]. Then its boundary will be
$$
\partial \partial S = \overline{\partial S} \setminus \mathring{\partial S}
$$
Since [[The boundary is a closed set]], this is equal to
$$
\partial \partial S = \partial S \setminus \mathring{\partial S}
$$


# $\mathring{\partial S} = \emptyset \implies \partial\partial S = \partial S$
Since the boundary has an empty interior by hypothesis, this yields
$$
\partial \partial S = \partial S
$$
# $\partial\partial S = \partial S \implies \mathring{\partial S} = \emptyset$
Suppose $\partial \partial S = \partial S$. Then
$$
\partial \partial S = \partial S \setminus \mathring{\partial S} = \partial S
$$
which can only hold if $\mathring{\partial S} = \emptyset$ ─because else, we'd only have that [[The boundary of the boundary is a subset of the boundary]] $\partial \partial S \subset \partial S$, differing by at least one point.

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)