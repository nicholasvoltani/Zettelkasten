---
date: 2023-07-01
tags:
  - mathematics
alias: Interior
---
up:: [[Topological Space]]

Given a topological space $(X, \tau)$ and a set $Z \subset X$, we denote its interior as the union of all open sets contained inside it. 

It's essentially "**inflating $Z$ from the inside-out**" with open sets.

$$
\mathring{Z} := \bigcup_{\substack{A \in \tau \\ A \subset Z}} A
$$
# Properties
- [[Interior preserves subset ordering]]
- [[All sets contain their interior]]
- [[The interior of an arbitrary union contains the union of the interiors]]
- [[The interior of a finite intersection is the intersection of the interiors]]

# Interiors from Closures
Given a "closure operator", one can infer its interior, since [[The interior is the complement of the closure of the complement]].


---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 27](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap27.pdf)