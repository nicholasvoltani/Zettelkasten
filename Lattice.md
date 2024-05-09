---
Date: 2023-08-01
Tags: mathematics
alias: 
---
up:: [[Universal Algebra]]

A triple $(X, \land, \lor)$ is said to be a lattice if its functions $\land (\lor): X \times X \to X$ satisfy the properties
- **Idempotency**: 
	- $\forall x \in X: x \land x = x$
	- $\forall x \in X: x \lor x = x$
- **Commutativity**:
	- $\forall x, y \in X: x \land y = y \land x$
	- $\forall x, y \in X: x \lor y = y \lor x$
- **Associativity**:
	- $\forall x,y,z \in X: (x \land y) \land z = x \land (y \land z)$
	- $\forall x, y, z \in X: (x \lor y) \lor z = x \lor (y \lor z)$
- **Absorption Laws**:
	- $\forall x, y \in X: x \land (x \lor y) = x$
	- $\forall x, y \in X: x \lor (x \land y) = x$
# Examples
![[Pasted image 20230801210428.png|200]]

Given a set $X$, its powerser $\mathbb{P}(X)$, alongside the intersection and union operators, can be thought of as a lattice. In it, the absorption rules are clear:
- $X \cap (X \cup Y) = X$
- $X \cup (X \cap Y) = X$

# Properties
For any lattice $(X, \land, \lor)$, it is true that
$$
x = x \land y \iff y = x \lor y
$$
$(\implies)$: $x = x\land y \implies x \lor y = (x \land y) \lor y = y$
$(\impliedby)$: $y = x \lor y \implies x \land y = x \land (x \lor y) = x$

From this, it follows that [[Every lattice induces a partial ordering]].

A lattice with global upper and lower bounds is said to be a [[Limited Lattice]], whose maximum and minimum we denote as $1$ and $0$, respectively.

When a lattice's operators **distribute**, such as
$$
\begin{align*}
a \land (b \lor c) &= (a \land b) \lor (a \land c)\\
a \lor (b \land c) &= (a \lor b) \land (a \lor c)
\end{align*}
$$
it is called a [[Distributive Lattice]]. 


---
### References
- [Notas para um Curso de Física-Matemática, João Carlos Alves Barata. Cap. 02](http://denebola.if.usp.br/~jbarata/Notas_de_aula/arquivos/nc-cap02.pdf)
- [discrete mathematics - absorption laws don't understand it with Venn diagrams - Mathematics Stack Exchange](https://math.stackexchange.com/questions/1566322/absorption-laws-dont-understand-it-with-venn-diagrams)