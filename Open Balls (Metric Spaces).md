---
Date: 2023-06-24
tags:
  - mathematics
alias: Metric Open Ball
---
up:: [[Metric Space]]

One can think about the definition of an *open ball* in a metric space as the set of all points equidistant (with respect to the space's [[Metric Function]]) to some base point.

Given a point $x \in X \neq \emptyset$, one can think about the open ball of radius $r$ around $x$ as
$$
B_r(x) = \{y \in X \mid d(x, y) < r\}
$$

With this definition of open balls, one can think about [[Open Sets in Metric Spaces]], which are sets which, for each point it contains, also contain some open ball around each of them. In this sense, **open balls are the generators of open sets**.

Examples of $d_1, d_{p_1 \in (1, 2)}, d_2, d_{p_2 > 2}, d_\infty$ in $\mathbb{R}^2$:

![[Pasted image 20230625154219.png|200]]

# Generalization to Topological Spaces
Open balls offer the motivation for the idea of [[Topology]]: instead of thinking about **open balls** as the generators of all open sets, one starts from the very set of all open sets itself, which is a subset of the power set $\mathbb{P}(X)$. 

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 24](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap24.pdf) 