---
Date: 2023-07-05
tags:
  - mathematics
---
up:: [[Closure (Topology)]]

![[Pasted image 20230705193948.png|500]]

Let $(X, \tau)$ be a [[Topological Space]], and $Z \subseteq X$ a subset.

Then, since [[All sets are contained inside their closure]], $Z \subseteq \overline{Z}$. 

Since [[Set Complements flip subset ordering]], we have that $\overline{Z}^c \subseteq Z^c$. Since $\overline{Z}$ is closed, $\overline{Z}^c$ is open, and equal to its own [[Interior (Topology)|Interior]]. Thus,
$$
(\overline{Z}^c)^\circ = \overline{Z}^c \subseteq (Z^c)^\circ
$$
By flipping again with complements, we arrive at
$$
\left[(Z^c)^\circ\right]^c \subseteq \overline{Z}
$$
which shows a closed set[^1], which is contained inside $Z$'s closure. However, since $\overline{Z}$ is the smallest closed set containing $Z$, then we have that
$$
\left[(Z^c)^\circ\right]^c = \overline{Z}
$$

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)

[^1]: Since the complement of an open set/interior is a closed set.