---
Date: 2021-08-26
Tags: mathematics 
---
$\newcommand{\I}{\mathcal{I}}$
# Definição: Interpretação
Uma interpretação é uma dupla $\mathfrak{I} = \left< D, \mathcal{I} \right>$, onde
- $D \neq \emptyset$ é o **domínio do discurso**;
- $\mathcal{I}$ é o **mapa de interpretação**, que age em [[Sintaxe de Lógica de Primeira Ordem|símbolos não-lógicos]] (funções e predicados $n$-ários) da forma:
## Interpretação de funções n-árias
Dada uma **função** $n$-ária $f$, $$\I[f]: \bigtimes\limits_{i=1}^n D \to D$$ 
Por exemplo, a função unária `bestFriend` induz, via $\I$, um mapa $D \to D$, que supostamente mapeia pessoas aos seus melhores amigos *sob esta interpretação*. 

Outro exemplo: uma interpretação da função (símbolo não-lógico) 1-ária `successor` nos números naturais induziria uma função (matemática)
$$\I(\text{successor}): n \mapsto n+1$$

## Interpretação de predicados n-ários
Dado um **predicado** $n$-ário $P$, $$\I[P] \subset D^n$$ 
Por exemplo, o predicado `Dog` induz, via $\I$, um subconjunto de $D$, supostamente o subconjunto de cachorros *sob esta interpretação*! 

Outro exemplo: a interpretação do predicado (símbolo não-lógico) 2-ário `SuccessorOf` nos números naturais induziria um conjunto do tipo
$$\I(\text{SuccessorOf}) = \{(1,0), (2,1), (3,2), (4,3), \dots\} \subseteq D^2$$

Equivalentemente, $\I$ induz uma função característica $$\chi_P: \bigtimes\limits_{i=1}^n D \to \{0, 1\}$$ sobre o domínio $D$, que supostamente "julga" se algum $d \in D$ "é um cachorro ou não" *sob esta interpretação*.

(Lembre-se que as funções consideradas no texto são **totais**, ou seja, estão definidas **em todo o domínio $D$**! Ou seja, mesmo uma pedra será passível de estar `Happy(pedra)` ou não; é um preço a se pagar pela regularidade.)

### Comentário sobre símbolos não-lógicos e interpretação
Note-se que é somente via uma **interpretação** $\mathfrak{I}$ que os **símbolos** de função/predicado tornam-se, de fato, uma **função/relação** (dentro da própria interpretação $\mathfrak{I}$). Sem uma interpretação, $f$ e $P$ são **meramente símbolos**!


## Referências
- BRACHMAN, Ronald J.; LEVESQUE, Hector J.; REITER, Raymond (Ed.). **Knowledge representation**. MIT press, 1992
