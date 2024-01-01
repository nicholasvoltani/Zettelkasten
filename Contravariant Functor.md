---
Date: 2023-08-05
Tags: mathematics
alias: Contravariant
---
up:: [[Functor]]

![[Contravariant Functor.excalidraw|400]]

A contravariant functor is a functor which flips morphisms in the target [[Category]]. It's usually denoted as
$$F: C^{op} \to D$$
where $C^{op}$ is the [[Opposite Category]] of $C$. 

Thus, formally, for each $x, y \in C$, we have that
$$f \in Hom_C(x, y) \iff F(f) \in Hom_D(F(y), F(x))$$
i.e. morphisms are flipped upon $F$'s influence.

# Examples
- When talking about [[Vector Space]]s and their relation to their [[Vector Space Dual]]s, it can be proven that [[The functor between vector spaces and their duals is contravariant]].

---
### References
- [What is a Functor? Definitions and Examples, Part 2](https://www.math3ma.com/blog/what-is-a-functor-part-2)