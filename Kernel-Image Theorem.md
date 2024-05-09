---
Date: 2023-07-28
Tags: mathematics
alias: Rank-Nullity Theorem
---
up:: [[Linear Transformation]]

> The [[Finitely Generated Vector Space Dimension|Dimension]] of a [[Vector Space]] is equal to the dimension of $T$'s [[Kernel (Group)|Kernel]] plus its [[Linear Transformation Rank]].

Given a linear transformation $T: U \to V$ whose domain is the [[Vector Space]] $(U, +, \cdot)$, we have that 
$$
\dim U = \dim (Im T) + \dim(\ker T)
$$
# Proof
Assume that $\dim U = n$, and that $\ker T \neq \{0\}$ at first. 

Then $\ker T$ will have a [[Hamel Basis]] $K = \{k_1, \dots, k_m\}$[^1]. 
Since [[Any linearly independent set can be extended to a Hamel basis]], we can extend it to a basis of $U$ itself by uniting with vectors $S = \{s_{m+1}, \dots, s_n\}$ outside of its span.
Thus, $B \equiv K \cup S$ is a basis for $U$.

Since [[A linear transformation's image of a basis spans its image]], we have that $T(B)$ is a [[Spanning Set]] for $Im T$ ─ but note that[^2]
$$
T(B) = T(S) = \{T(s_{m+1}), \dots, T(s_n))\}
$$
Thus, $Im T$ is spanned by the $n - m$ vectors in $T(S)$. We seek to prove that it is a basis ─ thus, that it is also linearly independent. Thus, we seek to prove that $\sum_k \alpha_k T(s_k) = 0 \iff \alpha_k = 0$.

Consider the [[Linear Combination]]
$$
\sum_{k = m+1}^n \alpha_k T(s_k) = T\left(\sum_{k = m+1}^n \alpha_k s_k\right)
$$
which implies that $\sum_{k = m+1}^n \alpha_k s_k \in \ker T$ ─ thus, it can be written as a linear combination of its basis $K$:
$$
\sum_{k = m+1}^n \alpha_k s_k = \sum\limits_{i=1}^m \alpha_i k_i \iff \sum\limits_{i=1}^m \tilde{\alpha}_i k_i + \sum_{k = m+1}^n \tilde{\alpha}_k s_k = 0
$$
where we invoke that $B = K \cup S$ is linearly independent, for which this sum only equals $0$ if all coefficients are also $0$. 

Thus, $T(S)$ is a basis for $Im T$, and we can conclude that
$$
\dim U = \dim \ker T + \dim Im T
$$
If $\ker T = \{0\}$, we need only consider a basis for $U$, for which we'll reach the same conclusion.

# Corollaries
- [[An endomorphism is injective iff it's surjective]]

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.

[^1]: Since it will have a linearly independent set, and since [[Every vector space which has a linearly independent set has a Hamel Basis containing this set]].
[^2]: Invokes that [[The image of the union is the union of the images]].