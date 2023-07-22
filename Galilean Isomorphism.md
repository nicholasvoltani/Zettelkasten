---
Date: 2023-07-21
Tags: mathematics
---
up:: [[Galilean Space]]

A map between galilean spaces $\varphi: \left(E, V, t, \left<\cdot, \cdot\right>\right) \to \left(E', V', t', \left<\cdot, \cdot\right>'\right)$ is a galilean isomorphism if
- it is an [[Affine Isomorphism]] with underlying linear isomorphism $L: V \to V'$, such that
- $L$ preserves time: $t' \circ L = t$
	- Note that any two points $P, Q \in E$ which are [[Simultaneous Events (Galilean)|Simultaneous Event]]s (i.e. $\overrightarrow{PQ} \in \ker(t)$) are also simultaneous in $E'$, since $$\overrightarrow{PQ} \in \ker(t) \implies t(\overrightarrow{PQ}) = t'(L(\overrightarrow{PQ})) \implies L(\overrightarrow{PQ}) \in \ker(t')$$
- $L$ preserves the inner product for [[Simultaneous Events (Galilean)|Simultaneous Event]]s in $E$ (i.e. for all $v \in \ker(t)$): $\left<L(v_1), L(v_2)\right>' = \left<v_1, v_2\right>$ for any $v_1, v_2 \in V$

---
### References
- 