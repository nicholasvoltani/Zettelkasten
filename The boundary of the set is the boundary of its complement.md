---
Date: 2023-07-20
Tags: mathematics
---
up:: [[Boundary (Topology)]]

![[The boundary of set is the boundary of its complement.excalidraw|300]]

Let $S \subseteq X$ be a set in a [[Topological Space]] $(X, \tau)$. Denote the [[Closure (Topology)|Closure]] by $\cdot^-$ and the [[Interior (Topology)|Interior]] as $\cdot^\circ$.

Then its [[Boundary (Topology)|Boundary]] is 
$$\partial S = S^- \setminus S^\circ = S^- \cap {S^\circ}^C$$
where $\cdot^C$ is the set's [[Set Complement|Complement]].

Using that [[The closure is the complement of the interior of the complement]] and flipping the intersection, we have
$$\partial S = {S^\circ}^C \cap {{S^C}^\circ}^C = {S^\circ}^C \setminus {(S^C)}^\circ$$
Using that [[The interior is the complement of the closure of the complement]] yields
$$\partial S = {S^\circ}^C \cap {{S^C}^\circ}^C = {{{S^C}^-}^C}^C \setminus {(S^C)}^\circ = {(S^C)}^- \setminus (S^C)^\circ = \partial (S^C)$$

Thus, $\partial S = \partial (S^C)$.