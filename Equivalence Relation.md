---
Date: 2023-06-29
Tags: mathematics
---
up:: [[020 MOC Mathematics]]

Given a set $X$, a function $\sim: X \times X \to \{True, False\}$ is an equivalence relation if it satisfies
1. **Reflexivity**: $\forall x \in X, x \sim x$
2. **Commutativity**: $\forall x, y \in X, x \sim y \iff y \sim x$
3. **Associativity**: $\forall x, y, z \in X, x \sim y \land y \sim z \implies x \sim z$

All points equivalent to each other belong to the same [[Equivalence Class]]
$$
[x] = \{y \in X \mid y \sim x\}
$$
Note that [[All equivalence classes are disjoint]], since having a single point in common makes them the same class.

# Examples
One can prove that [[All pseudometric spaces induce metric spaces]] via the equivalence relation $x \sim y \iff d(x,y) = 0$. 

Also, a function $f: X \to Y$ induces an equivalence relation of the sort $x \sim y \iff f(x) = f(y)$, partitioning its image into different "fragments" if points map to the same point.