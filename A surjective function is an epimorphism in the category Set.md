---
Date: 2023-07-30
Tags: mathematics
alias: 
---
up:: [[Epimorphism]]

Let $f: X \to Y$ and $g_1, g_2: Y \to Z$ be functions in the [[Category]] $Set$, such that $g_1 \circ f = g_2 \circ f$. We seek to prove that $f$ is surjective $\implies$ $g_1 = g_2$ under these conditions.

# Surjective $\implies$ Epimorphism
Assume $f$ is [[Surjective Function|Surjective]]. Then it'll follow that
$$
\forall y \in Y: \exists x \in X \mid y = f(x)
$$
Thus, for any $y \in Y$, we have that
$$
g_1(y) = g_1(f(x)) \overset{Hyp.}{=} g_2(f(x)) = g_2(y)
$$
And thus $f$ is an [[Epimorphism]].

# Epimorphism $\implies$ Surjective
Proof by contrapositive: Suppose $f$ is not surjective. Then there are points in $Y \setminus f(X)$ ─ let $\tilde{y} \in Y \setminus f(X)$.

Then we can construct functions $g_1, g_2: Y \to Z$ such that
$$
\begin{cases}
\forall x \in X: g_1(f(x)) = g_2(f(x))\\
g_1(\tilde{y}) \neq g_2(\tilde{y})
\end{cases}
$$
Thus, it would follow that $f$ is **not** an epimorphism, since there is some point in $Y$ such that they differ, regardless of their composition being equal.

Therefore, all epimorphisms $f$ are surjective (in the category $Set$).

---
### References
- [epimorphism in nLab](https://ncatlab.org/nlab/show/epimorphism)