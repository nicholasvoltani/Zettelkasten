---
Date: 2023-07-29
Tags: mathematics
alias: 
---
up:: [[Monomorphism]]

Let $f: X \to Y$ and $g_1, g_2: Z \to X$ be functions in the [[Category]] $Set$, such that $f \circ g_1 = f \circ g_2$. We seek to prove that $f$ is injective $\implies$ $g_1 = g_2$ under these conditions.

# Injective $\implies$ Monomorphism
Assume that $f$ is [[Injective Function|Injective]]. Then it'll follow that
$$
\forall z \in Z: f(g_1(z)) = f(g_2(z)) \implies \forall z \in Z: g_1(z) = g_2(z) \implies g_1 = g_2
$$
Thus, $f$ is a monomorphism.

# Monomorphism $\implies$ Injective
Let $f$ be a [[Monomorphism]]. Then for any two functions $g_1, g_2: Z \to X$, it'll follow that $(f \circ g_1 = f \circ g_2) \implies g_1 = g_2$, for **any** functions $g_1, g_2: Z \to X$.

The proof is "constructive": Let $x_1, x_2 \in X$ and some $\tilde{z} \in Z$. Then choose $g_1, g_2$ such that 

$$
\begin{cases}
g_1(z) = g_2(z) : z \neq \tilde{z}\\
g_1(\tilde{z}) = x_1\\
g_2(\tilde{z}) = x_2
\end{cases}
$$
that is, they are the same function, but they (may) differ for some $\tilde{z} \in Z$.

Then we have per hypothesis that
$$
\forall z \in Z: f(g_1(z)) = f(g_2(z)) \implies g_1(z) = g_2(z)
$$
In particular, we have that it follows for $\tilde{z}$:
$$
\begin{align*}
&f(g_1(\tilde{z})) = f(g_2(\tilde{z})) \implies g_1(\tilde{z}) = g_2(\tilde{z})\\
&\iff f(x_1) = f(x_2) \implies x_1 = x_2
\end{align*}
$$
Since this can be done for all points $x_1, x_2 \in X$, then $f$ is injective[^1].


---
### References
- [monomorphism in nLab](https://ncatlab.org/nlab/show/monomorphism)

[^1]: And, in fact, this proves that, given a monomorphism, we cannot construct $g_1, g_2$ as above such that they differ in a single point: the monomorphism condition ensures that they are necessarily equal to all points ─ provided that their composition with $f$ is equal.