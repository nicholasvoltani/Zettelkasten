---
date: 2023-07-27
tags:
  - mathematics
alias: Steinitz Exchange Lemma
---
up:: [[Finitely Generated Vector Space]]

Let $(V, +, \cdot)$ be a [[Vector Space]], with [[Spanning Set]] $S = \{s_1, \dots, s_n\}$. Let $U = \{u_1, \dots, u_m\} \subseteq V$ be a [[Linear Independence|Linearly Independent]] set. We seek to prove that $m \leq n$.

> We seek to prove that, by adequate arrangements, exchanges of vectors of $S$ with vectors from $U$ still make the new set a spanning set, since each vector removed can be seen as the linear combination of the remainder of the vectors (thus, "no information is lost").

**Proof by Induction**: removing a vector from $S$ and adding a vector from $U$ still makes their union a spanning set.
- $k=1$: $S \cup \{u_1\}$ is [[Linear Dependence|Linearly Dependent]] and spans $V$. Since [[A set is linearly dependent iff there is a vector which is a linear combination of previous vectors]], then we can rearrange the new set and remove some vector from $S$ such that this union still spans $V$ ─ say, removing $s_n$[^1] ─ yielding $\{u_1, s_1, \dots, s_{n-1}\}$.
- $k-1 \implies k$: Suppose that $\{u_1, \dots, u_{k-1}, s_1, \dots, s_{n-k-1}\}$ is still a spanning set, after having swapped $k-1$ vectors from $S$ for $k-1$ vectors from $U$ (provided adequate arrangements). Since it spans $V$, then we have that, in particular,
$$
u_k = \sum\limits_{i=1}^{k-1}\alpha_i u_i + \sum\limits_{i=1}^{n-k-1} \tilde{\alpha}_i s_i
$$
Note that we must have some $\tilde{\alpha}_i$ different than $0$, since else it would make $\{u_1, \dots, u_k\}$ linearly independent[^2] ─ let it be $\tilde{\alpha}_k$. Then we have
$$
s_k = \frac{1}{\tilde{\alpha}_k} \left(u_k -\sum\limits_{i=1}^{k-1}\alpha_i u_i + \sum\limits_{i=1}^{n-k-2} \tilde{\alpha}_i s_i\right)
$$
Thus, $s_k$ is in the span of $\{u_1, \dots, u_k, s_1, \dots, s_{n-k-2}\}$. As a consequence, this new set will still span $V$ (since it contains all vectors which, per hypothesis, span $V$).

At the end, we'll have the set $U \cup \{s_1, \dots, s_{n-m}\}$ which spans $V$. Note that, if $m > n$, we'd run out of spanning vectors $S$ and would be forced to remove vectors from $U$ themselves ─ which would make it [[Linear Dependence|Linearly Dependent]], contradiction.

Thus we must have that $m \leq n$.

# Corollaries
- [[All Hamel bases have the same number of elements (in a finitely generated vector space)]]
- [[Sets larger than a finitely generated space's bases are linearly dependent]]
- [[Any linearly independent set can be extended to a Hamel basis]]

---
### References
- [linear algebra - Prove that cardinality of linearly independent set is less than or equal to spanning set - Mathematics Stack Exchange](https://math.stackexchange.com/questions/3401970/prove-that-cardinality-of-linearly-independent-set-is-less-than-or-equal-to-span)
- [linear algebra - The length of every linearly independent list of vectors is less than or equal to the length of every spanning list of vectors. - Mathematics Stack Exchange](https://math.stackexchange.com/questions/2762576/the-length-of-every-linearly-independent-list-of-vectors-is-less-than-or-equal-t)

[^1]: This works since $s_k$ will be substituted by the span of the remaining vectors ─ and, thus, this new set will still span the entire set, just with $\{u_1, s_1, \dots, s_{n-1}\}$ instead of with $\{s_1, \dots, s_n\}$.
[^2]: And we have that [[A set is linearly independent iff all its finite subsets are also L.I.]].