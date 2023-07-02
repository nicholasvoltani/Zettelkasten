---
Date: 2023-07-01
Tags: mathematics
---
up:: [[020 MOC Mathematics]]

Given a function $f: X \to Y$ and a subset $A \subset X$, we say the image of $A$ is the set of all points in $Y$ which are reached by $f$ from $A$.

Formally, it is
$$f(A) = \{y \in Y \mid \exists a \in A :f(a) = y\}$$

Thus, when talking about points in the image of some subset, 
$$y \in f(A) \iff \exists x \in A \mid f(x) = y$$

Note that [[Every function is surjective with respect to its image]], since all points in the image are, per definition, reached by some point in its domain.

# Properties
- [[The image of the union is the union of the images]]
- [[The image of the intersection is contained in the intersection of the images]]
	- [[The injective image of intersections is the intersection of images]]
- [[The image of the complement contains the complement of the images]]
	- [[The injective image of complements is the complement of images]]
- [[The image of the preimage of a set is contained in the set]]
- [[The preimage of the image of a set contains the set]]