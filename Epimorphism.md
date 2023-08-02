---
Date: 2023-07-29
Tags: mathematics
alias: 
---
up:: [[Category]]

An epimorphism is a generalization of a [[Surjective Function]], since [[A surjective function is an epimorphism in the category Set]].

![[Epimorphism.excalidraw|250]]

Given a category $C$ and a morphism $f \in Hom(X, Y)$, we say that $f$ is an epimorphism if
$$\forall g_1, g_2 \in Hom(Y, Z): (g_1 \circ f = g_2 \circ f) \implies g_1 = g_2$$
That is, if they are "equal" after composing with $f$, then they were equal all along.

# Related
- Epimorphisms in $C$ are [[Monomorphism]]s in the [[Opposite Category]] $C^{op}$.

---
### References
- [epimorphism in nLab](https://ncatlab.org/nlab/show/epimorphism)