---
Date: " 2023-10-10"
tags:
  - physics
aliases:
---
up:: [[Torque]]

Only external torques affect a center of mass's angular momentum:
$$
\frac{d\vec{L}}{dt} = \sum_i \vec{\tau}_i^{(e)}
$$
# Proof
It is assumed that the origin is at a point $O$, and all positions are measured with respect to $O$.
$$
\frac{d\vec{L}}{dt} = \sum_i \left(\underbrace{\dot{\vec{r}}_{i} \times \vec{p}_{i}}_{=0} + \vec{r}_{i} \times \dot{\vec{p}}_{i}\right)
$$
To each particle $i$, this amounts to [[Newton's Second Law]]:
$$
\dot{\vec{p}}_{i} = \sum_{j \neq i} \vec{F}_{j \to i} + \vec{F}_i^{(e)}
$$
which results into
$$
\begin{align*}
\frac{d\vec{L}}{dt} &= \sum_i \vec{r}_{i} \times \left(\sum_{j \neq i} \vec{F}_{j \to i} + \vec{F}_i^{(e)}\right)\\
&= \sum_{\substack{i, j\\ i \neq j}} \vec{r}_i \times \vec{F}_{j \to i}+ \sum_i \vec{r}_i \times \vec{F}_i^{(e)}
\end{align*}
$$

By [[Newton's Third Law]], we have that $\vec{F}_{j \to i} = - \vec{F}_{i \to j}$, which will yield terms of the form
$$
\sum_{\substack{i, j\\ i\neq j}} (\vec{r}_i - \vec{r}_j) \times \vec{F}_{i \to j} = 0
$$
since they are parallel vectors.
