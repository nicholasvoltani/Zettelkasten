---
Date: 2023-08-01
tags:
  - mathematics
alias: 
---
up:: [[Lattice]]

A [[Universal Algebra]] $(A, \{\land, \lor, \lnot, 1, 0\})$ is said to be a Boolean Algebra if it satisfies the properties:
- $(A, \land, \lor)$ is a [[Distributive Lattice|Distributive]] and [[Limited Lattice]] ($\forall x \in X: x \land 0 = 0, x \lor 1 = 1$)
- To every point $x \in X$, there is a unique complement $\lnot x \in X$

It is assured to have unique complement, since [[Every distributive and limited lattice has unique complements]].

# Properties
## De Morgan Laws
Every boolean algebra satisfies the **De Morgan laws**:
$$
\begin{cases*}
\lnot (a \land b) = \lnot a \lor \lnot b\\
\lnot(a \lor b) = \lnot a \land \lnot b
\end{cases*}
$$

To prove the first equation[^1]:
$$
\begin{align*}
(a \land b) \land (\lnot a \lor \lnot b) &= a \land [(b \land \lnot a) \lor (b \land \lnot b)]\\
&= a \land (b \land \lnot a)\\
&= (a \land \lnot a) \land b\\
&=0
\end{align*}
$$
Since every element in $X$ has unique complement, we have that $\lnot (a \land b) = \lnot a \lor \lnot b$.

# Examples
- [[Measurable Space]]s are examples of boolean algebras with elements from its [[Sigma-algebra]].

---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 02](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap02.pdf)

[^1]: The proof of the second equation follows from proving the first, by switching all elements $a \to \lnot a$, $b \to \lnot b$.