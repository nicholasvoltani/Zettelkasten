---
Date: 2023-07-27
Tags: marxism
---
up:: [[Linear Transformation]]

Let $T:U \to V$ be a linear transformation. Denote its [[Kernel (Group)|Kernel]] by $\ker T$.

# Injective $\implies$ Trivial kernel
Proof by contrapositive: Let $\ker T \neq \{0\}$. Then there is some other vector $v \in V$ such that
$$v \neq 0 \mid T(v) = T(0) = 0$$
Thus, $T$ cannot be [[Injective Function|Injective]], since $v$ and $0$ have the same value.

# Trivial kernel $\implies$ Injective
Let $\ker T = \{0\}$. Let $u, v \in V$ such that $T(u) = T(v)$. Then, since it is a linear transformation, we have that
$$T(u-v) = 0 \implies u-v \in \ker T \implies u-v = 0 \implies u = v$$
Thus, $T$ is injective. 
