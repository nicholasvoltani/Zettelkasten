---
Date: Thursday, 26-08-2021 @ 21:29
Tags:
---
# Definição: Interpretação
Uma interpretação é uma dupla $\mathfrak{I} = \left< D, \mathcal{I} \right>$, onde
- $D \neq \emptyset$ é o **domínio do discurso**
- $\mathcal{I}$ é o **mapa de interpretação**, que age em funções e predicados $n$-ários da forma
	- Dada uma função $n$-ária $f$, $\I[f] = \tilde{f}: \bigtimes\limits_{i=1}^n D \to D$ 
(por exemplo, a função unária `bestFriend` induz, via $\I$, um mapa $D \to D$, que supostamente mapeia pessoas aos seus melhores amigos)
	- Dado um predicado $n$-ário $P$, $I[P] \subset D^n$ 
(por exemplo, o predicado `Dog` induz, via $\I$, um subconjunto de $D$, supostamente o subconjunto de cachorros! Equivalentemente, $I$ induz uma função característica $\chi_P: \bigtimes\limits_{i=1}^n D \to \{0, 1\}$ sobre o domínio $D$, que supostamente "julga" se algum $d \in D$ "é um cachorro ou não")

(Lembre-se que as funções consideradas no texto são **totais**, ou seja, estão definidas **em todo o domínio $D$**!)

### Comentário sobre símbolos não-lógicos e interpretação
Note-se que é somente via uma **interpretação** $\mathfrak{I}$ que os **símbolos** de função/predicado tornam-se, de fato, uma **função/relação** (dentro da própria interpretação $\mathfrak{I}$). Sem uma interpretação, $f$ e $P$ são **meramente símbolos**!


## Referências
- BRACHMAN, Ronald J.; LEVESQUE, Hector J.; REITER, Raymond (Ed.). **Knowledge representation**. MIT press, 1992
