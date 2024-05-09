---
Date: 2023-07-02
tags:
  - mathematics
---
up:: [[Closure (Topology)]]

Let $(X, \tau)$ be a [[Topological Space]], and $U \subseteq V \subseteq X$, and let $\overline{U}, \overline{V}$ be their [[Closure (Topology)|closures]]. 

Since $U \subseteq V$, it is "smaller" than $V$, and thus it is expected that the amount of closed sets which contain it will be higher to/the same as the amount which enclose $V$. 

We can see it as follows: let $\mathcal{F}_{U, V}$ be the collection of closed sets which enclose $U, V$. Then we have that
$$
\mathcal{F}_{U} = \mathcal{F}_V \cup \{F \in \mathcal{F}(\tau) \mid (U \subseteq F) \land (V \nsubseteq F)\}
$$
Since we expect $\mathcal{F}_{U} \supseteq \mathcal{F}_{V}$, we prove that
$$
\overline{U} = \bigcap\limits_{\mathcal{F}_{U}} F \subseteq \bigcap\limits_{\mathcal{F}_{V}}F = \overline{V}
$$

Thus, closures preserve subset ordering.