---
Date: 2023-07-27
Tags: mathematics
alias: 
---
up:: [[Linear Transformation]]

Let $T: U \to V$ be a linear transformation.

# Injective $\implies$ Preserves linear independence
Let $T$ be [[Injective Function|Injective]]. Then, since [[A linear transformation is injective iff its kernel is trivial]], $\ker T = \{0\}$.

Let $\{v_i\}$ be a [[Hamel Basis]] in $V$. Then 
$$
T(0) = T\left(\sum_i \alpha_i v_i\right) = \sum_i \alpha_i T(v_i)
$$
can only happen if all $\alpha_i = 0$. Thus, $\{T(v_i)\}$ is [[Linear Independence|Linearly Independent]] in $W$.

# Preserves linear independence $\implies$ Injective
Per hypothesis, $T$ preserves linear independence from any linearly independent subset $\{v_i\}_{i=1}^n \subset V$. In particular, since [[Every vector space which has a linearly independent set has a Hamel Basis containing this set]], it will preserve linear independence from a [[Hamel Basis]] $\mathcal{B}$ (which [[Spanning Set|Span]]s $V$).

For $\mathcal{B} = \{b_i\}_i$, we have that $\sum_i \alpha_i b_i = 0 \iff \alpha_i = 0$, which is maintained by $T$. Thus,
$$
\sum_i T(\alpha_i b_i) = 0 \iff \alpha_i = 0 
$$
Thus, $T(v) = 0 \iff v = 0$, and thus $T$ is injective.

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.