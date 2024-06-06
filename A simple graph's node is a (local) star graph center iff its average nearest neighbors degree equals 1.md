---
date: " 2024-06-02"
tags:
  - mathematics
aliases:
---

up:: [[Star Graph]]

The [[Average Nearest Neighbors' Degree]] of a node $i$ (in a [[Simple Graph]]) measures how close $i$ is to a star graph's center.  In other words, $k_{nn}$ measures how the vicinity of $i$ compares to a star graph.

# $i$ is a (local) star graph center $\implies$ $k_{nn}(i) = 1$
Let $i$ be the center of a local star graph. Then this means that its neighbors connect *exclusively* to $i$, i.e. all their [[Node Degree]]s are equal to $1$. Thus, their sum is equal to $i$'s degree (since this is a [[Simple Graph]] and undirected, i.e. no self-loops and at most one link between nodes).

# $k_{nn}(i) = 1 \implies$ $i$ is a (local) star graph center
Let $k_{nn}(i) = 1$. Then this means that $i$'s [[Node Degree]] is not empty, i.e. it has neighbors. Thus, we can infer that
$$
\sum\limits_{<j>}k(j) = k(i)
$$
But note that $i$'s degree is equal to how many neighbors it has, i.e. $k(i) = \sum_{<j>} 1$. 

Therefore
$$
\sum_\limits{<j>} \left(k(j) - 1\right) = 0
$$
Since we have that $k(j) \geq 1$ (since it has at least $i$ as its neighbor), then we have that $k(j) - 1 \geq 0$. Therefore, each term in this sum must be individually equal to zero. 

Thus, each of $i$'s neighbors connect exclusively to it. Thus, $i$ is the center of a local star graph.