---
Date: 2023-07-07
Tags: mathematics
---
up:: [[021 MOC Algebra]]

A **left-** group action of a [[Group (Mathematics)|Group]] $(G, +)$ over some set $X$ is the function
$$\alpha: G \times X \to X$$
which satisfies the properties:
- **Identity**: $\alpha(e_G, x) \equiv e_G \cdot x= x$
- **Compatibility**: $g \cdot (h \cdot x) \equiv \alpha(g, \alpha(h,x)) = \alpha(gh, x) \equiv (gh) \cdot x$


# Right group action
A **right-** group action is the function
$$\alpha_r: X \times G \to X$$
which satisfies the same properties.

# Properties
A group action induces an [[Orbit of Group Action|Orbit]] over a point $x \in X$, which is the set
$$Orb_x = \{g\cdot x \in X:\forall g \in G\} \subseteq X$$
Note that [[Group actions induce an equivalence relation over a set's orbits|Group actions partition a set into its orbits]], since their connection via a group element induces an [[Equivalence Relation]].

Also, every point $x \in X$ has a [[Stabilizer of Group Action|Stabilizer]] which keep it intact:
$$Stab_x = \{g \in G \mid g \cdot x = x\} \subseteq G$$
## Properties of group elements from a group action
For any point $a, b \in X$ which are connected via the group action, as $b = g \cdot a$, then we have that
$$a = e \cdot a = (g^{-1}g) \cdot x = g^{-1} \cdot (g \cdot x) = g^{-1} \cdot b$$
Thus, we have that
$$b = g \cdot a \iff a = g^{-1} \cdot b$$

# Types of Group Action
A group action is a [[Transitive Group Action]] if it's a group action which allows transitivity between points in the set.

A group action is said to be a [[Free Group Action]] if the only element which stabilizes all elements in $X$ is the identity of $G$.

---
### References
- [Group action - Wikipedia](https://en.wikipedia.org/wiki/Group_action)
- [https://kconrad.math.uconn.edu/blurbs/grouptheory/gpaction.pdf](https://kconrad.math.uconn.edu/blurbs/grouptheory/gpaction.pdf)