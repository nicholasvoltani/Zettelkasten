---
Date: 2023-08-21
Tags: mathematics
alias: 
---
up:: [[027 MOC Category Theory]]

![[Case where initial object isomorphic to terminal object.excalidraw|300]]

We have that every [[Initial Object]] $I$ has a unique morphism coming out of it towards any other object in a [[Category]] $C$, and that every [[Terminal Object]] $T$ has a unique object coming into it. Thus, there is only one morphism from $I$ to $T$; call it $I \overset{f}{\to} T$. 

In the case where $\exists \varphi \in Hom(T,I)$[^1], we can see that
$$
\begin{cases}
1_I &= f; \varphi\\
1_T &= \varphi ; f
\end{cases}
$$
Therefore, we have that $\varphi$ is the inverse of $f$ ─ therefore, $f$ is an isomorphism.
# Corollaries
When there is a morphism from a terminal object to an initial object, we have that they are isomorphic. In this case, they will be isomorphic to a [[Zero Object]]. Thus, there can only be one zero object (up to isomorphism) in a category.

---
### References
- KASHIWARA, Masaki; SCHAPIRA, Pierre, **Categories and Sheaves**, Berlin, Heidelberg: Springer Berlin Heidelberg, 2006.

[^1]: Note that this doesn't make $T$ stop being a terminal object; it is an additional property that it possesses, aside from being terminal.