---
Date: 2023-07-20
Tags: mathematics
---
up:: [[Affine Isomorphism]]

![[Translations in affine spaces are affine automorphisms.excalidraw|400]]

Let $(E, V, +_E)$ be an [[Affine Space]], and let $T_w: E \to E$ be the translation of all points in $E$ by $w \in V$ (i.e. $T_w(P) = P + w$). It defines an [[Affine Map]] with underlying linear map[^1]
$$\begin{align*}
L: V &\to V\\
v &\mapsto v
\end{align*}$$
such that one can see the map as
$$T_w(P+v) = T_w(P) + L(v) = T_w(P) + v$$
Note that this is the case, since the diagram commutes. Let $P, Q$ be points connected by $v$ ─ i.e. $Q = P + v$. Then we have that
$$T_w(Q) = Q + w = (P + v) + w = \dots = T_w(P) + v = T_w(P) + L(v)$$
since the [[Group Action]] is "compatible" ─ $(A+v) + w = A + (v + w)$ ─, alongside the additive group $(V, +)$ being [[Abelian Group|Abelian]].

Thus, this is an [[Affine Isomorphism]], since its inverse is
$$\begin{align*}
T_w^{-1}: E &\to E\\
P &\mapsto P + (-w)
\end{align*}$$
with underlying linear map 
$$\begin{align*}
L^{-1}: V &\to V\\
v &\mapsto v
\end{align*}
$$

---
### References
- 

[^1]: Note that this works since, for any group action, $Q = P + v \iff P = Q + (-v)$