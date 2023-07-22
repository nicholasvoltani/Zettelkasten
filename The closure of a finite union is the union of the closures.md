---
Date: 2023-07-05
Tags: mathematics
---
up:: [[Closure (Topology)]]

Let $(X, \tau)$ be a [[Topological Space]].
Proof by induction:
1. Let $M, N \subseteq X$. Note that, since [[All sets are contained inside their closure]], we have that $M, N \subseteq \overline{M}, \overline{N}$, which implies that $M \cup N \subseteq \overline{M} \cup \overline{N}$
2. Let $\bigcup\limits_{i=1}^n M_i \subseteq \bigcup\limits_{i=1}^n \overline{M_i}$. Then, as above, $\bigcup\limits_{i=1}^n M_i \cup M_{n+1} \subseteq \bigcup\limits_{i=1}^{n+1} \overline{M_i}$

## Counterexample of closure of infinite unions
Let $M_i = (-1-\frac{1}{n}, 1+\frac{1}{n}), n\geq 2$.
- $\overline{M_i} = \left[-1-\frac{1}{n}, 1+\frac{1}{n}\right]$ whose infinite union is $(-1, 1)$
- $\bigcup\limits_{n=2}^\infty M_i = (-1, 1)$, whose closure is $[-1, 1]$

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)