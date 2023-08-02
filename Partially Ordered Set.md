---
Date: 2023-07-27
Tags: mathematics
alias: Partially Ordered, Poset, Partial Ordering
---
up:: [[020 MOC Mathematics]]

A set $X$ is partially ordered if it has a partial order $\leq$. That is, this relation is
- **Reflexive**: $\forall x \in X: x \leq x$
- **Transitive**: $\forall x, y, z \in X: (x \leq y) \land (y \leq z) \implies x \leq z$
- **Antisymmetric**: $\forall x, y \in X: (x\leq y) \land (y \leq x) \implies x = y$

# Examples
- Given any set $X$, one can induce a partial order in its power set $\mathcal{P}(X)$ by the subset $\subseteq$ relation. Note that it is not total in general.

# Related
- A set $X$ is a [[Totally Ordered Set]] if any two elements in $X$ can be compared by this order relation.
- An element $x_0 \in X$ is said to be **maximal** if $\forall x \in X: x \neq x_0 \implies x \leq x_0$.
	- An example of a maximal element is a union of subsets ${X_i} \subseteq \bigcup_i X_i$
- An element $m \in A \subseteq X$ is an **upper bound** of $A$ if all elements in $A$ are bounded by $m$ ─ $\forall a \in A: a \leq m$

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.