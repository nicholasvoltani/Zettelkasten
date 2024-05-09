---
Date: 2023-06-29
tags:
  - mathematics
---
up:: [[Pseudometric Space]]

A function $\tilde{d}: M \times M \to \mathbb{R}^+_0$ is said to be a pseudometric if it satisfies:
1. **Self-non-degeneracy**: $\forall x \in X, d(x,x) = 0$
2. **Triangle Inequality**: $\forall x,y,z \in X, d(x, z) \leq d(x, y) + d(y, z)$
3. **Positivity**: $\forall x, y \in X, d(x,y) \geq 0$
4. **Commutativity**: $\forall x,y \in X, d(x,y) = d(y,x)$

It is essentially a [[Metric Function]] but with the possibility of different points with distance equal to $0$. 

# Sufficient conditions for a metric
One can shrink these conditions to two:
1. $\forall x \in X, d(x,x) = 0$
2. **(Modified) Triangular Inequality**: $\forall x,y,z \in X, d(x, z) \leq d(x, y) + d({\color{red} z, y})$

From those two, one can prove the other conditions:
- $1 \land 2 \implies 3$: $0 = d(x,x) \leq d(x,y) + d(x,y) \,\, \square$
- $1 \land 2 \implies 4$: $d(x,y) \leq d(x,x) + d(y,x)$ and $d(y,x) \leq d(y,y) + d(y,x) \,\,\square$ 

Note that [[Every metric function is a pseudometric function]], since metrics are more specific (have more properties) than pseudometrics.

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 24](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap24.pdf) 