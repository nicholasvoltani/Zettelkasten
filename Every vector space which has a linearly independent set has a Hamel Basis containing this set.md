---
date: 2023-07-27
tags:
  - mathematics
alias: 
---
up:: [[Hamel Basis]]

Let $(V, +, \cdot)$ be a [[Vector Space]], and let $S \subset V$ be a [[Linear Independence|Linearly Independent]] set. We seek to prove that there is a Hamel basis which will be the "maximal" linearly independent subset of $V$, via Zorn's Lemma.

Consider the class of **linearly independent subsets** of $V$, $\mathcal{P}$. It is not empty by hypothesis, since $S \subseteq \mathcal{P}$.

# Zorn's Lemma's condition
We need to prove that, for all [[Totally Ordered Set|Totally Ordered]] subsets of $\mathcal{P}$, they have an upper bound. 

Thus, let $\{A_\alpha\}_{\alpha \in \Lambda} \subset \mathcal{P}$ ─ which means it is a collection of linearly independent sets which all are comparable via the partial ordering $\subseteq$. A candidate for its upper bound is 
$$
\mathcal{A} \equiv \bigcup_{\alpha \in \Lambda} A_\alpha
$$To prove that it is linearly independent, let a finite subset of it $\{v_i\}_{i=1}^n \subseteq \mathcal{A}$. Per definition, all $v_i$'s are in some $A_{\alpha_i}$. Since they have a total ordering relation, we can order these subset such that
$$
A_{\alpha_1} \subseteq \dots \subseteq A_{\alpha_n}
$$
in such a way that $\{v_i\}_{i=1}^n \subset A_{\alpha_n}$. Since [[A set is linearly independent iff all its finite subsets are also L.I.]] and $A_{\alpha_n}$ is L.I. per hypothesis, then $\{v_i\}_{i=1}^n$ is also L.I.. Thus, $\mathcal{A}$ is an element of $\mathcal{P}$ and is an upper bound of $\{A_{\alpha_i}\}_{\alpha \in \Lambda}$.

# Conclusion
By [[Zorn's Lemma]], $\mathcal{P}$ has a maximal element ─ call it $\mathcal{B}$. It is a linearly independent set, and it also spans $V$ ─ since, if it didn't, there'd be some vector $v \in V$ outside of its [[Spanning Set|Span]]. Since [[The union of a linearly independent set with a vector outside of its span is also linearly independent]], we'd have some element $\mathcal{B} \cup \{v\} \in \mathcal{P}$ such that $\mathcal{B} \subseteq \mathcal{B} \cup \{v\}$, which is a contradiction to $\mathcal{B}$ being a maximal element of $\mathcal{P}$.

Thus, all vector spaces (finitely generated or not) which have some linearly independent set, will also have a [[Hamel Basis]].

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho & Mary Lilian Lourenço. Editora EDUSP.