---
date: 2023-07-05
tags:
  - mathematics
---
up:: [[Interior (Topology)]]

Let $(X, \tau)$ be a [[Topological Space]].
Proof by induction:
1. Let $M, N \subseteq X$. Note that, since [[All sets contain their interior]], we have that $\mathring{M}, \mathring{N} \subseteq M,N$, which implies that $\mathring{M} \cup \mathring{N} \subseteq M \cup N$
2. Let $\bigcup\limits_{i=1}^n \mathring{M_i} \subseteq \bigcup\limits_{i=1}^n M_i$. Then, as above, $\bigcup\limits_{i=1}^n \mathring{M_i} \cup \mathring{M_{n+1}} \subseteq \bigcup\limits_{i=1}^{n+1} M_i$

## Counterexample of interior of infinite intersections
Let $M_i = [-\frac{1}{n}+1, 1+\frac{1}{n}], n\geq 2$ (sets around $x=1$)
- $\mathring{M_i} = (-\frac{1}{n}+1, 1+\frac{1}{n})$ whose infinite intersection is ${1}$
- $\bigcap\limits_{n=2}^\infty M_i = {1}$, whose interior is $\emptyset$


---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)