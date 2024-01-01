---
Date: 2023-08-20
Tags: mathematics
alias: 
---
up:: [[027 MOC Category Theory]]

![[Pasted image 20230820210901.png|200]]

Given a [[Category]] $C$, we say an object $I \in Ob(C)$ is an **initial object** if all objects $x \in C$ have a morphism **from** $I$ to $x$. That is,

$$\forall x \in C: \exists f \in Mor(I, x): I \overset{f}{\to}x$$
# Properties
- An initial object is a [[Terminal Object]] in the [[Opposite Category]] $C^{op}$.
- [[A terminal object is isomorphic to an initial object if there is a morphism from T to I]].
- An initial object which is also terminal is called a [[Zero Object]].

---
### References
- KASHIWARA, Masaki; SCHAPIRA, Pierre, **Categories and Sheaves**, Berlin, Heidelberg: Springer Berlin Heidelberg, 2006.
- [Summary of Truth about Types, a talk by Bartosz Milewski - Rakhim.org](https://rakhim.org/summary-of-truth-about-types-a-talk-by-bartosz-milewski/)