---
date: 2023-08-20
tags:
  - mathematics
alias: 
---
up:: [[028 MOC Category Theory]]

![[Pasted image 20230820211612.png|200]]

Given a [[Category]] $C$, we say an object $T \in Ob(C)$ is a **terminal object** if all objects $x \in C$ have a morphism **to** $T$ from $x$. That is,

$$
\forall x \in C: \exists f \in Mor(x, T): x \overset{f}{\to} T
$$
# Properties
- A terminal object is an [[Initial Object]] in the [[Opposite Category]] $C^{op}$.
- [[A terminal object is isomorphic to an initial object if there is a morphism from T to I]].
- An initial object which is also terminal is called a [[Zero Object]].

---
### References
- KASHIWARA, Masaki; SCHAPIRA, Pierre, **Categories and Sheaves**, Berlin, Heidelberg: Springer Berlin Heidelberg, 2006.
- [Summary of Truth about Types, a talk by Bartosz Milewski - Rakhim.org](https://rakhim.org/summary-of-truth-about-types-a-talk-by-bartosz-milewski/)