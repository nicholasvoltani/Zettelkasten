---
Date: 2023-07-01
Tags: mathematics
---
up:: [[020 MOC Mathematics]]

The intuition is that the preimage of a set can be bigger than the set itself (due to different points mapping to the same output).

Let $f: X \to Y$ be a function, and $A \subseteq X$ a subset.

Let $x \in A$. Then
$$x\in A {\color{red} \implies} f(x) \in f(A)$$
that is, $f(x)$ is in its [[Image of Function|image]].

By the definition of the [[Preimage of Function]] $f$, this is equivalent to
$$x \in f^{-1} (f(A))$$
# Counterexample of equality
![[Pasted image 20230701151408.png|500]]

Note that $f(x) \in f(A)$ need not imply that $x \in A$: there can be some point $c \in X \setminus A$ such that $f(c) \in f(A)$. That is why [[The injective preimage of the image of a set contains the set]].

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 01](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap01.pdf) 