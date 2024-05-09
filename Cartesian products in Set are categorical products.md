---
Date: 2023-08-21
Tags: mathematics
alias: 
---
up:: [[Product (Category)]]

![[Pasted image 20230821211433.png|300]]

Given two sets $X_1, X_2$, denote their cartesian product as $X_1 \times X_2$, and let
$$
\pi_i: X_1 \times X_2 \to X_i
$$
be the respective **projection maps**.

Let $Y$ be another set. 
# Every function to the cartesian product is completely determined by the projection maps
Let $h: Y \to X_1 \times X_2$ be any map.

Then it is uniquely determined by its values under composition with the projection maps, since
$$
\forall y \in Y: (\pi_i \circ h)(y) = \tilde{x_i}(y) \in X_i
$$
# Functions to coordinate sets uniquely induce factor map to cartesian product
Conversely, let  $f_i: Y \to X_i$ functions from $Y$ to each "coordinate" set $X_i$. Then there is a unique map $h: Y \to X_1 \times X_2$ such that
$$
\pi_i \circ h = f_i: Y \to X_i
$$
In fact, it is of the form
$$
h(y) = (f_1(y), f_2(y)) \in X_1 \times X_2
$$
which is uniquely determined by $f_i$ and which satisfies the condition above.
# Conclusion
Note that to every function 
$$
h: Y \to X_1 \times X_2
$$
there is a unique function 
$$
\begin{align*}
f_1 \times f_2:& Y \times Y \to X_1 \times X_2\\
& (y, y) \mapsto \left(f_1(y), f_2(y)\right)
\end{align*}
$$
where $f_i = \pi_i \circ h: Y \to X_i$ are uniquely determined by $h$. 

Thus, there is an isomorphism between the [[Hom-Set]]s $Hom(Y, X_1 \times X_2)$ and $Hom(Y \times Y, X_1 \times X_2)$.

---
### References
- MAC LANE, Saunders, **Categories for the Working Mathematician**, New York, NY: Springer New York, 1978.