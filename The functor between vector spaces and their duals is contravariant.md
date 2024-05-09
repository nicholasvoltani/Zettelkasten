---
Date: 2023-08-05
tags:
  - mathematics
alias: 
---
up:: [[Contravariant Functor]]

![[Pasted image 20230805175856.png|300]]

One can create a [[Functor]] between the [[Vect Category]] and their [[Vector Space Dual]]s (i.e. their respective [[Hom-Set]]s to their underlying [[Field (Algebra)|Field]] $\mathbb{K}$).

![[Pasted image 20230805180659.png|200]]

That is, given [[Vector Space]]s $V \overset{f}{\to} W$ related by a morphism $f$, we seek to know the form of $F(f)$. As it turns out,
$$
F(f): W^* \to V^*
$$
not the other way around, which makes $F$ a [[Contravariant Functor]]. We denote $F(f) \equiv f^*$: it is called $f$'s [[Pullback]]. 

The way $F(f)$ acts is as follows: For any [[Linear Operator]] $\varphi: W \to \mathbb{K}$, we have that 
$$
f^*(\varphi) = \varphi \circ f: V \to \mathbb{K}
$$
Finally, for any $v \in V$, we have that
$$
f^*(\varphi)(v) = \varphi(f(v)) \in \mathbb{K}
$$
# Functorial properties
For any two morphisms 
$$
V_1 \overset{T_1}{\to} V_2 \overset{T_2}{\to} V_3
$$
we have that, given some $\varphi: V_3 \to \mathbb{K}$,
$$
\begin{align*}
F(T_2 \circ T_1)(\varphi) &= (T_2 \circ T_1)^*(\varphi) \\
&= \varphi \circ (T_2 \circ T_1) \\
&= (\varphi \circ T_2) \circ T_1 \\
&= T_2^*\circ (\varphi \circ T_1) \\
&= (T_2^* \circ T_1^*)(\varphi) \\
&= F(T_2) \circ F(T_1)(\varphi)
\end{align*}
$$

Thus, we have that $F(T_2 \circ T_1) = F(T_2) \circ F(T_1)$, and $F$ satisfies a functor's properties.

---
### References
- [What is a Functor? Definitions and Examples, Part 2](https://www.math3ma.com/blog/what-is-a-functor-part-2)