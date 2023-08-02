---
Date: 2023-08-01
Tags: mathematics
alias: 
---
up:: [[Lattice]]

Let $(X, \land, \lor)$ be a [[Distributive Lattice|Distributive]] and [[Limited Lattice|Limited]] lattice.

Given $x \in X$, we seek to prove that, to any $y, y' \in X$ such that $x \perp y$ and $x \perp y'$ implies that $y = y'$.

We have that
$$\begin{cases*}
x \land y &= 0\\
x \lor y &= 1\\
x \land y' &= 0\\
x \lor y' &= 1
\end{cases*}
$$

# 1) $y' \leq y$
$$x \lor y = 1 \implies (x \lor y) \land y' = y' = (x \land y') \lor (y \land y') = y \land y'$$
Therefore, $y' = y \land y' \implies y' \leq y$, by the [[Partially Ordered Set|Partial Ordering]] induces by the lattice.

# 2) $y \leq y'$
$$x \lor y' = 1 \implies (x \lor y') \land y = y = (x \land y) \lor (y' \land y) = y' \land y$$
Therefore, $y = y \land y' \implies y \leq y'$. 

Thus, $y = y'$, and every point in $X$ has a unique complement.

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 02](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap02.pdf)