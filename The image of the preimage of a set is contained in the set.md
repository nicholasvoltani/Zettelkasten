---
Date: 2023-07-01
Tags: mathematics
---
up:: [[Image of Function]]

Let $f: X \to Y$ be a function, and $B \subseteq Y$ a subset.

Let $y \in f(f^{-1}(B))$. Then, by the definition of [[Image of Function]], we have that 
$$\exists x \in f^{-1}(B) \mid f(x) = y$$

By the definition of [[Preimage of Function]], we have that this implies that $f(x) = y \in B$. 

# Counterexample of equality
![[Pasted image 20230701152748.png|500]]

Note that $y \in B$ need not imply that $f^{-1}(y) \subseteq X$: for all points $c \in Y \setminus f(X)$ we have $f^{-1}(c) = \emptyset$. That is why [[The surjective image of the preimage of a set is contained in the set]].

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 01](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap01.pdf)>)