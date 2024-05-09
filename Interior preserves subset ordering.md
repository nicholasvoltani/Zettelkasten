---
Date: 2023-07-03
tags:
  - mathematics
---
up:: [[Interior (Topology)]]

Let $(X, \tau)$ be a [[Topological Space]], and $U \subseteq V \subseteq X$, and let $\mathring{U}, \mathring{V}$ be their [[Interior (Topology)|Interior]]s. 

Since $U \subseteq V$, it is "smaller" than $V$, and thus it is expected that the amount of open sets which it contains will be lower to/the same as the amount which $V$ contains. 

We can see it as follows: let $\mathcal{T}_{U, V}$ be the collection of open sets which are contained inside $U, V$. Then we have that
$$
\mathcal{T}_{V} = \mathcal{T}_U \cup \{A \in \tau \mid (A \subseteq V) \land (A \nsubseteq U)\}
$$
Since we expect $\mathcal{T}_{V} \supseteq \mathcal{T}_{U}$, we prove that
$$
\mathring{U} = \bigcup\limits_{\mathcal{T}_{U}} F \subseteq \bigcup\limits_{\mathcal{T}_{V}}F = \mathring{V}
$$

Thus, interiors preserve subset ordering.
