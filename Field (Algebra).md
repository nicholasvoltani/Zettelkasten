---
Date: 2023-07-16
Tags: mathematics
alias: Field
---
up:: [[021 MOC Algebra]]

A field is a triple $(\mathbb{K}, +, \cdot)$, where $\mathbb{K}$ is a (non-empty) set with operations $+$ and $\cdot$ which satisfy
1. Addition is commutative, associative, has neutral element $0_\oplus$ and inverses
2. Multiplication is commutative, associative, has neutral element $1_\odot$ and inverses for all elements in $\mathbb{K} \setminus \{0\}$
3. Addition and multiplication are distributive: $(a+b) \cdot c = a\cdot c + b \cdot c$

# Properties
Note that a field, then, is an [[Abelian Group]] under $(\mathbb{K}, +)$, as well as under $(\mathbb{K} \setminus \{0\}, \cdot)$, alongside the distributive property for both operations.

This implies that, since [[A group's identity is unique]] and [[All elements of a group have a unique inverse]], $0_\oplus$ and $1_\odot$ are unique, as well as its inverses under $+$ and $\cdot$.

## Additive identity = multiplicative $0$
Note that one can identify the $0$'s of $+$ and $\cdot$ with the field's $0$. Denote them as $0_\oplus$ and $0_\odot$. Then, since for any $k \in \mathbb{K}$,
$$
0_\oplus = k - k = 1\cdot k - 1\cdot k = (1-1)\cdot k = 0_\odot \cdot k
$$
it follows that $0 = 0_\oplus \iff 0 =  0_\odot$. Thus, we can write it unambiguously as $0$.

## Multiplicative identity = additive $1$
Analogously, the $1$'s of $+$ and $\cdot$ are the same as the field's $1$. Denote them as $1_\oplus$ and $1_\odot$. Then, since for any $k \in \mathbb{K}$,
$$
k = 1_\odot \cdot k = (0_\oplus + 1_\oplus) \cdot k = 1_\odot \cdot k
$$
$$1_\oplus = 1_\oplus + 0 = 1_\odot \cdot 1_\oplus$$

it follows that $1 = 1_\odot \iff 1 = 1_\oplus$. Thus, we can write it unambiguously as $1$. 

## Only $0$ makes a multiplication go to $0$
Given any elements $a, b \in \mathbb{K}$, one has that
$$
a\cdot b = 0 \iff (a=0) \lor (b=0)
$$
The converse is trivial; the direct implication comes from the following considerations:
- If both $a$ and $b$ are equal to $0$, then the implication holds
- If $a \neq 0$, then it has an inverse $a^{-1}$, from which we can multiply on both sides to yield $b = 0$
- Analogously if $b \neq 0$, then it has an inverse $b^{-1}$, from which we can multiply on both sides to yield $a = 0$

Thus, this is a direct consequence from the fact that $0$ has no multiplicative inverse.

---
### References
- **Um Curso de Álgebra Linear**, Flávio Ulhoa Coelho, Mary Lilian Lourenço. Editora EDUSP. 