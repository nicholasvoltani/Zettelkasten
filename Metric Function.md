---
Date: 2023-06-24
Tags: mathematics
---
up:: [[Metric Space]]

A function $d: X \times X \to \mathbb{R}^+_0$ over some set $X$ is a metric if it satisfies the following properties:
1. **Non-degeneracy**: $d(x, y) = 0 \iff x = y$ 
2. **Triangle Inequality**: $\forall x,y,z \in X, d(x, z) \leq d(x, y) + d(y, z)$
3. **Positivity**: $\forall x, y \in X, d(x,y) \geq 0$
4. **Commutativity**: $\forall x,y \in X, d(x,y) = d(y,x)$

# Sufficient conditions for a metric
One can shrink these conditions to two:
1. **Non-degeneracy** (as above)
2. **(Modified) Triangular Inequality**: $\forall x,y,z \in X, d(x, z) \leq d(x, y) + d({\color{red} z, y})$

From those two, one can prove the other conditions:
- $1 \land 2 \implies 3$: $0 = d(x,x) \leq d(x,y) + d(x,y) \,\, \square$
- $1 \land 2 \implies 4$: $d(x,y) \leq d(x,x) + d(y,x)$ and  $d(y,x) \leq d(y,y) + d(y,x) \,\,\square$ 

# Examples of metrics
## Euclidean spaces $\mathbb{R}^n$
The initial motivation for metric spaces comes from $\mathbb{R}^n$ with the Euclidean metric
$$d_E(u, v) = \sqrt{\sum\limits_{i=1}^n (u_i - v_i)^2}$$

## Trivial metric
An example of a metric borne out of this general definition is the trivial metric: 
$$d_t(x,y) = \begin{cases} 0 \; \mathrm{if}\;  x=y\\ 1 \;\mathrm{if} \; x \neq y \end{cases}$$

## Supremum norm and distances in function space
Consider $X = C([0,1])$ the set of all continuous functions over $[0,1]$, and define the supremum norm as
$$d_\infty(f, g) = \sup\limits_{x \in [0,1]} |f(x) - g(x)|$$


---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 24](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap24.pdf) 