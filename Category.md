---
Date: 2023-07-28
Tags: mathematics
alias: 
---
up:: [[027 MOC Category Theory]]

![[Pasted image 20230728213419.png|300]]

A category $C$ is composed of:
1. A class of elements called **objects**, denoted $Ob(C)$
2. For each pair of objects $x, y \in Ob(C)$, a class of elements called **morphisms between $x$ and $y$** $Hom(x,y)$ (called [[Hom-Set]] of morphisms from $x$ to $y$ ─ though it need not be a set)[^1]
3. For each pair of morphisms $f \in Hom(x, y), g \in Hom(y, z)$, a morphism $g \circ f \in Hom(x,z)$, called their **composite**
4. For each object $x$, an **identity morphism** $1_x \in Hom(x,x)$

The rules that apply to a category are:
1. Composition of morphism is **associative**: $(f \circ g) \circ h = f \circ (g \circ h)$
2. Identity morphism acts as **two-sided composition identity**: $\forall f \in Hom(x, x): 1_x \circ f = f \circ 1_x = f$

# Properties
- To every category $C$ there is an [[Opposite Category]] $C^{op}$ which is the same category but with all morphisms flipped


---
### References
- [category in nLab](https://ncatlab.org/nlab/show/category)
- [Category (mathematics) - Wikipedia](https://en.wikipedia.org/wiki/Category_(mathematics))

[^1]: The class of all morphisms in $C$ is the disjoint union of all $Hom(x, y)$, for all $x, y \in Ob(C)$.