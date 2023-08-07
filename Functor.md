---
Date: 2023-08-05
Tags: mathematics
alias: Covariant Functor, Covariant
---
up:: [[Category]]

![[Functor.excalidraw|200]]

A functor is essentially a "translation" of what happens inside a category $C$ into another category $D$.

Given categories $C, D$, a functor is a morphism $F: C \to D$ which preserves their structure:
1. All objects in $C$ are mapped to objects in $D$
2. All morphisms in $a \overset{f}{\to} b$ are mapped to morphisms in $F(a) \overset{F(f)}{\to} F(b)$
3. The functor acts as a [[Group Homomorphism|Homomorphism]] of sorts, preserving the algebraic composition of morphisms: 
	1. $F(g \circ f) = F(g) \circ F(f)$ 
	2. $F(1_a) = 1_{F(a)}$

# Properties
![[Pasted image 20230805175113.png|300]]

Functors can either be covariant or [[Contravariant Functor|Contravariant]], depending on whether its action "flips" morphisms in the target category or not.
# Examples
- A [[Group Homomorphism]] between [[Group (Mathematics)|Group]]s $G, H$ can be seen as a functor between their respective single-element categories $BG, BH$
- [[Group Actions can be seen as functors]] from a groupoid with a single element onto another category $F: G \to C$

---
### References
- [What is a Functor? Definition and Examples, Part 1](https://www.math3ma.com/blog/what-is-a-functor-part-1)