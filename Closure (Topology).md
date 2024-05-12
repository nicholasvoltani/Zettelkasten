---
date: 2023-07-01
tags:
  - mathematics
alias: Closure
---
up::[[Topological Space]]

Given a topological space $(X, \tau)$ and a set $Z \subset X$, we denote its interior as closure as the intersection of all closed sets contained inside it. 

It's essentially "**crunching $Z$ from the outside-in**" with closed sets.

$$
\overline{Z}:= \bigcap\limits_{\substack{F \in \mathcal{F}(\tau)\\  Z \subseteq F}} F
$$
# Properties
- [[Closure preserves subset ordering]]
- [[All sets are contained inside their closure]]
- [[The closure of a finite union is the union of the closures]]
- [[The closure of an arbitrary intersection is contained in the intersection of the closures]]

# Closures from Interiors
Note that, given an "interior operator", one can infer its closure, since [[The closure is the complement of the interior of the complement]].

# Relation to continuity
Via the definition of a [[Topologically Continuous Function]] $f: X \to Y$, one knows that it "preimages" open sets to open sets, and also closed sets to closed sets.

Denote the closure of a set $A$ in $X$'s topology as as $Cl_X(A)$. Then, phrased another way, [[The closure of a continuous image of a closure is the closure of the image|Continuous functions map close inputs to close outputs]].

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)