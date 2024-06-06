---
date: " 2024-01-11"
tags:
  - physics
aliases:
  - O(1,3)
---
up:: [[032 MOC Relativity]]

The Lorentz Group, denoted $O(1, 3)$, is composed of all transformations in Minkowski space which preserve the [[Invariant Interval (Relativity)]]. 

That is, for any [[Minkowski Metric]] $g_{\mu \nu}$, we have that $\Lambda$ is a [[Lorentz Transformation]] if
$$
\Lambda^T g \,\Lambda = g \iff \Lambda^{\color{red} \alpha}_\mu  \,g_{{\color{red} \alpha} {\color{green} \beta}} \,\Lambda^{\color{green} \beta}_\nu = g_{\mu \nu}
$$
# $O(1, 3)$ is a group
Let $\Lambda_1, \Lambda_2 \in O(1, 3)$. Then 
$$
(\Lambda_1 \Lambda_2)^T \, g \, (\Lambda_1 \Lambda_2) = g
$$
Trivially the identity matrix $\mathbb{1}$ belongs to $O(1,3)$.

Given $\Lambda \in O(1, 3)$, its inverse $\Lambda^{-1}$ also satisfies this condition:
$$
\begin{align}
(\Lambda^{-1})^T \, g \, \Lambda^{-1} &= (\Lambda^{-1})^T \, (\Lambda^T \, g \, \Lambda) \, \Lambda^{-1} \\
&= (\Lambda \Lambda^{-1})^T \, g \,(\Lambda \Lambda^{-1})\\
&= g
\end{align}
$$
# Properties
- Rotations belong to the Lorentz Group, since we have that they preserve distances (since they are [[Orthogonal Transformation]]s, satisfying $R^T R = \mathbb{1}$) and, thus, trivially preserve the invariant interval
	- Thus, the dimension of $O(1, 3)$ is $6$: $3$ independent rotations and $3$ independent boosts
- [[Proper Lorentz Group]] $SO(1,3)$
- [[Restricted Lorentz Group]] $SO^+(1,3)$ 

---
### References
- [Special Relativity - David Tong](http://www.damtp.cam.ac.uk/user/tong/relativity/seven.pdf)