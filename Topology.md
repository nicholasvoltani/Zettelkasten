---
Date: 2023-06-23
Tags: mathematics
---
up:: [[Topological Space]]

A topology over a set $X$ is a set $\tau$ such that
1. $\emptyset, X \in \tau$
2. **Algebraically closed under arbitrary unions**: $\forall \{B_i\}_{i \in \Lambda} \subset \tau, \bigcup\limits_{i \in \Lambda} B_i \in \tau$
3. **Algebraically closed under finite intersections**: $\forall \{B_i\}_{i =1}^n \subset \tau, \bigcap\limits_{i=1}^n B_i \in \tau$

These properties were motivated by the properties satisfied by [[Metric Topology]]'s.

# Examples of topologies
For a given set $X \neq \emptyset$, some elementary topologies are:
- **Trivial (chaotic) topology** $\tau_t = \{\emptyset, X\}$
- **Discrete topology** (powerset) $\tau_d = \mathbb{P}(X)$

---
### References
- Sutherland, Wilson A. **Introduction to metric and topological spaces**. Oxford University Press, 2009.
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)