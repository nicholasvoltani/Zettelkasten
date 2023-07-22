---
Date: 2023-07-03
Tags: mathematics
---
up:: [[Interior (Topology)]]

Let $(X, \tau)$ be a [[Topological Space]], and $S \subseteq X$.

Then, by the definition of [[Interior (Topology)]], we know that $\mathring{S}$ is the union of open sets which are contained in $S$. 

Since all of them are contained in $S$, their union will also be inside $S$. The "lower bound" of its interior is $\emptyset$, since $\emptyset$ is closed; the "upper bound" is $S$ itself, since all open sets involved are $\subseteq S$; thus, $\emptyset \subseteq \mathring{S} \subseteq S$.

*Ad absurdum*, suppose $\exists x \in \mathring{S} \mid x \notin S$. 
Then $\exists A \subseteq S \mid x \in A \implies x \in S$, absurd.