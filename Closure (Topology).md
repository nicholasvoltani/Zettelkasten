---
Date: 2023-07-01
Tags: mathematics
---
up::[[Topological Space]]

Given a topological space $(X, \tau)$ and a set $Z \subset X$, we denote its interior as closure as the intersection of all closed sets contained inside it. 

It's essentially "**cruncing $Z$ from the outside-in**" with closed sets.

$$\overline{Z}:= \bigcap\limits_{\substack{F \in \mathcal{F}(\tau)\\  Z \subseteq F}} F$$
# Relation to continuity
Via the definition of a [[Topologically Continuous Function]] $f: X \to Y$, one knows that it "preimages" open sets to open sets, and also closed sets to closed sets.

Denote the closure of a set $A$ in $X$'s topology as as $Cl_X(A)$. Then, phrased another way, a function is (topologically) continuous if
$$\forall A \subseteq Y, Cl_X(f(A)) \subseteq Cl_Y{f(A)}$$ 

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)