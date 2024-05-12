---
date: 2021-10-10
tags:
  - mathematics 
---
# Pragmatismo em Lógica de Primeira Ordem
Em Lógica de Primeira Ordem, desejamos um sistema que não só consiga codificar seu conhecimento sobre o universo (em que está inserido) via uma [[Sintaxe de Lógica de Primeira Ordem|sintaxe]] e uma [[Semântica de Lógica de Primeira Ordem|semântica]] apropriados, mas também que consiga **fazer inferências** sobre consequências lógicas de suas verdades primeiras. 

## Consequência Lógica
Temos que, dada uma interpretação $\mathfrak{I} = \left<\mathcal{D}, \mathcal{I}\right>$, nosso sistema tem seu conhecimento codificado através de suas **sentenças** (fórmulas sem variáveis livres), as quais são ou verdadeiras ou falsas universalmente (no universo de discurso $\mathcal{D}$).

Suponhamos que nosso sistema tem um conjunto de sentenças $S$, e que $\alpha \in S$ seja verdadeira sob a interpretação acima. Então temos que  
$$
\alpha \lor \lnot \beta
$$
é uma **[[Consequência Lógica em LPO|consequência lógica]]** de $S$ (em particular, por causa de $\alpha$), independente de qual $\beta \in S$ seja, e o denotamos por
$$
(S \models \alpha \lor \lnot \beta) \iff (\forall \mathfrak{I}. \, \mathfrak{I} \models S \implies \mathfrak{I} \models \alpha)
$$

Ou seja, temos que $\alpha$ é uma consequência lógica de $S$ sempre que tivermos uma interpretação na qual $S$ seja verdadeiro, e que isso implique em que $\alpha$ também seja verdadeiro. 

## Validade lógica
Dizemos que uma sentença é **logicamente válida** quando ela é consequência lógica do **conjunto vazio**; o denotamos por
$$
\models \alpha
$$
Ou seja, $\alpha$ é "válida" se e somente se for consequência lógica **de toda e qualquer interpretação $\mathfrak{I}$**.

## Validade lógica é caso especial de consequência lógica ($VL \implies CL$)
Note-se que $\alpha$ ser uma *validade lógica* quer dizer que é verdadeiro **para qualquer interpretação *whatsoever***, enquanto ele ser uma *consequência lógica* de uma sentença $S$ depende de que tal conjunto de sentenças **seja verdadeiro em certas interpretações**. Ou seja, validade lógica é um caso bem específico de uma consequência lógica. 

## Crenças explícitas e implícitas
O conjunto de sentenças dadas inicialmente ao sistema serão suas *crenças explícitas*, seu ponto de partida. Suas *crenças implícitas* serão as consequências lógicas que ele conseguir inferir a partir de **relações entre suas sentenças verdadeiras** (que estejam elas próprias sentenças em sua *Knowledge Base*). 

Por exemplo, dado `Dog(fido)`, nosso sistema somente poderá obter a conclusão lógica `Mammal(fido)` se ele acreditar na relação
$$
\forall x. \, \text{Dog}(x) \supset \text{Mammal}(x)
$$
pois pode ser que em sua interpretação, em particular, não seja o caso em que variáveis que satisfaçam `Dog`, satisfaçam também `Mammal`. 

---
### Referências
- BRACHMAN, Ronald J.; LEVESQUE, Hector J.; REITER, Raymond (Ed.). **Knowledge representation**. MIT press, 1992.