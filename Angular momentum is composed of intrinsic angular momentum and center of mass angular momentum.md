---
Date: " 2023-10-07"
tags:
  - physics
aliases:
---
up:: [[Angular Momentum]]

**Given an origin $O$**, a system of particles has total angular momentum
$$
\vec{L} = \sum_i \vec{r}_{i; CM} \times \vec{p}_{i;CM}+ \vec{R_O} \times \vec{P}
$$
where variables $\vec{x}_{i; CM}$ are centered on the [[center of mass]] and uppercase ones are referring directly to the CoM's properties (with respect to the origin $O$). **This assumes that all particles' masses are constant!**

# Proof
Given an origin $O$, each particle has position[^1]
$$
\vec{r}_{i; O} = \vec{R} + \vec{r}_{i; CM}
$$
with $i;O (CM)$ denoting the $i$-th particle's position with respect to $O$ (CM); $\vec{R}$ is measured with respect to $O$.

The total angular momentum is the sum of all angular momenta
$$
\vec{L} = \sum\limits_i \vec{r}_i \times \vec{p}_i = \sum\limits_i m_i \vec{r}_i \times \dot{\vec{r}}_i
$$
Opening with above equations yields, and using $\vec{R} = \sum_i m_i \vec{r}_i / M$,
$$
\vec{L} = \vec{R} \times \vec{P} + \sum\limits_i m_i \vec{r}_{i;CM} \times \dot{\vec{R}}  + \vec{R} \times \sum\limits_i m_i \dot{\vec{r}}_{i;CM} + \sum\limits_i m_i \vec{r}_{i;CM} \times \dot{\vec{r}}_{i;CM}
$$
The second term equals $0$, since
$$
\sum_i m_i (\vec{r}_i - \vec{R}) = M\vec{R} - M \vec{R} = 0
$$
The third term equals $0$ **provided that all masses are constant in time**.

# Corollaries
- A system of particles always has a [[Spin Angular Momentum]] which is independent of the [[Reference Frame]] (i.e. choice of origin). Thus, the "most natural" frame is the one centered on the [[Center of Mass]], in which it is the only term of $\vec{L}$
- 


[^1]: $\vec{r}_{i; CM}$ points from the center of mass to particle $i$.