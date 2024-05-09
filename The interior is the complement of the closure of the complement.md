---
Date: 2023-07-05
Tags: mathematics
---
up:: [[Interior (Topology)]]

![[Pasted image 20230705195120.png|500]]

Let $(X, \tau)$ be a [[Topological Space]], and $Z \subseteq X$ a subset.

Then, since [[All sets contain their interior]], $Z^\circ \subseteq Z$. 

Since [[Set Complements flip subset ordering]], we have that $Z^c \subseteq (Z^\circ)^c$. Since $Z^\circ$ is open, $(Z^\circ)^c$ is closed, and equal to its own [[Closure (Topology)|Closure]]. Thus,
$$
(Z^c)^- \subseteq (Z^\circ)^c
$$

By flipping again with complements, we arrive at
$$
Z^\circ \subseteq \left[(Z^c)^-\right]^c
$$
which shows an open set[^1], which contains $Z$'s interior. However, since $Z^\circ$ is the largest open set contained in $Z$, then we have that
$$
Z^\circ = \left[(Z^c)^-\right]^c
$$

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)

[^1]: Since the complement of an open set/interior is a closed set.