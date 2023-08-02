---
Date: 2023-07-29
Tags: mathematics
alias: 
---
up:: [[Category]]

A monomorphism is a categorical generalization of an [[Injective Function]], since [[An injective function is a monomorphism in the category Set]].

![[Monomorphism.excalidraw|250]]

Given a category $C$ and a morphism $f \in Hom(X, Y)$, we say that $f$ is a monomorphism if
$$\forall g_1, g_2 \in Hom(Z, X): (f \circ g_1 = f \circ g_2) \implies g_1 = g_2$$
That is, if they are "equal" after "pre-composition" with $f$, then they were equal all along.

# Related
- Monomorphisms in $C$ are [[Epimorphism]]s in the [[Opposite Category]] $C^{op}$.

---
### References
- [monomorphism in nLab](https://ncatlab.org/nlab/show/monomorphism)