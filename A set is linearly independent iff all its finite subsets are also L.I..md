---
Date: 2023-07-27
tags:
  - mathematics
alias: 
---
up:: [[021a MOC Linear Algebra]]

Let $(V, +, \cdot)$ be a [[Vector Space]], and $S \subset V$. Then we have that $S$ is [[Linear Independence|Linearly Independent]] iff all of its subsets are linearly independent.

This follows from the contrapositive of [[A set is linearly dependent iff there is a vector which is a linear combination of previous vectors]] (provided adequate rearrangements of the set $S$).

# Constructive proof
## Entire set is L.I. $\implies$ All finite subsets are L.I.
Let $S$ be linearly independent. Then, for all finite combinations of $\{v_1, \dots, v_k\} \subseteq S$, we'll have that their [[Linear Combination]] will only be zero when all of them are multiplied by $0$ ─ which makes all of these finite subsets L.I. in their own right.

## All finite subsets are L.I. $\implies$ Entire set is L.I.
Proof by contrapositive: assume the entire set is [[Linear Dependence|Linearly Dependent]]. Then there is some finite combination of vectors in $\{v_1, \dots, v_k\} \subseteq S$ such that, for at least some $j$, $\alpha_j \neq 0$, for which we have
$$
v_j = -\sum\limits_{i\neq j} \frac{\alpha_i}{\alpha_j} v_i
$$
Thus, there is some subset $\{v_1, \dots, v_k\} \subset S$ which is L.D..