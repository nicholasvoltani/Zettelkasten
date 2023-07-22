---
Date: 2023-07-09
Tags: mathematics
---
up:: [[Free Group Action]]

![[Free Group Action induces bijection between group and orbit.excalidraw|400]]

Let there be a [[Free Group Action]] of a [[Group (Mathematics)|Group]] $G$ over some set $X$.

Let $x \in X$, and $Orb_x$ its [[Orbit of Group Action|Orbit]].

Construct a map
$$\begin{align*}
\varphi: G& \to Orb_x\\
&g \mapsto g \cdot x
\end{align*}
$$

Note that [[Group actions induce a surjection between the group and a point's orbit]], since all points $g \cdot x \in Orb_x$ have at least some $g \in G$ from which they get from $x$ to $g \cdot x$. 

If the action is free, then $\varphi$ must be injective. Let $g \cdot x = h \cdot x \in Orb_x$. Then $x = (g^{-1} h) \cdot x$, for which $g^{-1} h = e_G \iff g = h$ (due to the action being free).

Thus, free group actions induce a bijection between $G$ and a point's orbit $Orb_x$.