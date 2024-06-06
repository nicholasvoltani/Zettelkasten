---
date: " 2024-05-18"
tags:
  - essay
aliases:
---

up:: [[027 MOC Calculus]]

Essa é uma apresentação que fiz para pessoas de Humanas como um primeiro contato ao Cálculo Diferencial e Integral, em fevereiro de 2024. Obviamente não possui toda o rigor de uma apresentação *matemática*, porém não é este seu propósito; serve como uma *apresentação* desta disciplina a pessoas que tendem a procurar a história/sociologia/filosofia/etc que permeiam as descobertas matemáticas, acanhando-se sempre de ver **a Matemática** de fato envolvida. Esta apresentação é, portanto, mais parecida com uma "terapia de choque" ─ porém num bom sentido (espero)!

---
# O que é um limite?
![[polygons_to_circle(1).png]]

Seja $P_n$ um polígono de $n$ lados, e $C$ um círculo. *Conforme $n$ aumenta*, $P_n$ *se aproxima* de um círculo $C$. 

Em notação matemática, escreveríamos
$$
\lim\limits_{n \to \infty} P_n = C
$$
a ser lido como "conforme $n$ *tende a infinito*, $P_n$ se aproxima de $C$". Em outras palavras, conforme $n$ aumenta arbitrariamente, $P_n$ parece-se arbitrariamente próximo de $C$. Obviamente, no exemplo acima, "parecer com $C$" não é precisamente "bem definido", mas espero que a visualização faça com que o conceito seja claro.

Inclusive, perceba, conforme for lendo, que os verbos que são utilizados não são mera coincidência: "tender a", "se aproximar de", são verbos que indicam *movimento* ─ no fim das contas, essa é a essência do Cálculo.

## Limites de funções
![[function_limit.png]]

Note que, na imagem, conforme $x$ **se aproxima de** $a$ (eixo horizontal), $f(x)$ **se aproxima de** $L$ (eixo vertical/altura). Escrevemos isso como
$$
\lim\limits_{x \to a} f(x) = L
$$

Caso $L = f(a)$, dizemos que $f$ **é contínua no ponto $a$**. É similar à noção cotidiana de algo ser "contínuo": um movimento contínuo sobre uma superfície é um movimento que consegue ocorrer desimpedido em seu processo, de seu começo a seu fim, por assim dizer. Inclusive, muitas pessoas aprendem que uma função é contínua quando consegue-se escrever ela "sem tirar a caneta do papel" enquanto se desenha ela.

## Uma função descontínua
Destaque-se, porém, que nem sempre o limite $L$ de uma função é igual a seu valor no ponto! Ou seja, existem funções que não são contínuas, como, por exemplo, 
$$
f(x) = \frac{\sin(x)}{x}
$$
![[Pasted image 20240518183034.png]]

Note que não podemos calcular $f(0)$, pois não podemos dividir por $0$; porém, ela possui um limite conforme[^1] $x \to 0$ (é uma demonstração comum em Cálculo, através do chamado "teorema do sanduíche"/"*squeeze theorem*").

# O que é uma integral?
A definição usual do que é uma integral é "a área debaixo de uma curva", a qual pode ser calculada através da soma de vários retângulos cujas larguras *tendem a $0$*, como a área de um semi-círculo[^2]:
![[MyPlotScene.mp4]]

Enfim, pode-se ver que podemos calcular a área debaixo de curvas através dessa soma de retângulos cada vez mais finos[^3] ─ ou seja, a integral é o *limite* dessa soma de retângulos (de largura $\Delta x$ e altura $f(x)$). Denotamos esse limite como
$$
\int\limits_a^b f(x) d x = \lim\limits_{\Delta x \to 0} \sum f(x) \Delta x
$$
O símbolo da integral é $\int$, que era um *S* originalmente mas foi "alongando-se" ao longo do tempo (não sei por quê). Note-se que denota-se a "fronteira" dentro da qual estamos buscando a área debaixo da curva: queremos a área de $f(x)$ com $a \leq x \leq b$, denotado por $\int_a^b \dots$

Destaque-se que $\int_a^b f(x) dx$ é para ser lido como se fosse, de fato, uma soma: estamos somando infinitos retângulos de altura $f(x)$ e "largura" $dx$, com a ressalva de que o tamanho de $dx$ é "infinitesimal", tem "largura $0$". Não é rigoroso dizer isso, mas é a ideia do que está acontecendo: $dx$ é como se fosse o limite da largura dos retângulos que vamos contraindo paulatinamente, de forma a obter uma medida mais e mais assertiva da área sob a curva. Embora os retângulos individuais tenham suas respectivas áreas indo a $0$, em conjunto elas formam um "*continuum*" que compõe a área da curva, algo que é, por assim dizer, "maciço", não-nulo. 

# O que é uma derivada?
## O problema das velocidades médias
A velocidade média com que se percorre uma distância $\Delta s$ em um intervalo de tempo $\Delta t$ é definida como
$$
v_m = \frac{\Delta s}{\Delta t}
$$
Por si só, essa medida pode ser contraproducente quando $\Delta s = 0$ mas $\Delta t \neq 0$, i.e. em funções não-lineares. Por exemplo:
![[Pasted image 20240518200823.png]]

Pensando na "velocidade média" dessa função acima, entre $x = -1$ e $x = 2$, teríamos que
$$
v_m = \frac{\Delta y}{\Delta x} = \frac{0 - 0}{2 - (-1)} = 0
$$

O problema é visível pelo gráfico: vemos que a função muda de uma maneira que não é linear, e velocidades médias medem variações lineares ─ por isso é uma variação *média*! Buscamos, então, uma forma mais fidedigna de medir variações de funções, uma forma mais assertiva e "fina" o suficiente.

## Definição de Derivada
$$
\frac{d f}{d t} = \lim\limits_{\Delta t \to 0} \frac{f(t + \Delta t) - f(t)}{\Delta t}
$$

Uma visualização gráfica explica muito bem o que é o conceito de derivada: ela é o *limite* de uma velocidade média. Quando falamos de uma "velocidade média", estamos essencialmente medindo o coeficiente de uma reta, e retas sempre precisam de (ao menos) dois pontos para serem definidas; é por isso que a *velocidade em um dado instante* é um limite, é uma *tendência* à qual o movimento aproxima-se, conforme mede-se de maneira mais e mais "granular". 

![[TangentLine.mp4]]

Uma forma que gosto de pensar é a seguinte: para saber da posição de algum objeto[^4], preciso de ao menos uma "fotografia" sua, que indique sua posição e tempo com relação a algum ponto de referência fixo. Para saber sua velocidade, preciso de ao menos duas fotografias (com respectivos tempos), e a partir delas eu posso "extrapolar" o quão rápido ele deslocou-se entre uma e outra. É óbvio de pensar que, se eu tirar fotos em intervalos de dias, minha extrapolação será menos "fiel" ao movimento de fato do que se eu tirá-las, digamos, num intervalo de segundos. Aqui é importante também notar que, se eu tirar três fotos, eu posso extrapolar como sua velocidade variou: posso estimar uma velocidade média entre as fotos 1 e 2, e outra velocidade entre as fotos 2 e 3, e portanto uma aceleração (variação da velocidade) média entre ambos os pares de fotos; *mutatis mutandis* referente à discussão acima, tais extrapolações serão mais fidedignas conforme suas medições forem "mais granulares". Essa é a intuição da derivada, que é um *limite* de uma variação média: o limite é justamente o mais "granular" que pode-se chegar nestas "medições" (obviamente ideais).

## Derivadas fundamentais
### Função constante
A derivada de uma função constante 
$$
c(x) = c
$$
é $0$, pois
$$
\frac{d c}{d t} = \lim\limits_{\Delta t \to 0} \frac{c - c}{\Delta t} = 0
$$
Isso corresponde a que a inclinação (ou "coeficiente angular") de uma função constante é $0$, ou seja, horizontal.

### Função linear
A derivada de uma função linear
$$
f(t) = at + b
$$
com $a, b \in \R$, é
$$
\begin{align*}
\frac{d f}{d t} &= \lim\limits_{\Delta t \to 0} \frac{a(t + \Delta t) + b - (at + b)}{\Delta t}\\
&= \lim\limits_{\Delta t \to 0} a \frac{\Delta t}{\Delta t} = a
\end{align*}
$$
Ou seja, a derivada de uma função linear é o próprio coeficiente angular dela.

### Função quadrática e além
A derivada de uma função quadrática
$$
f(t) = t^2
$$
é 
$$
\begin{align*}
\frac{d f}{d t} &= \lim\limits_{\Delta t \to 0} \frac{(t + \Delta t)^2 - t^2}{\Delta t}\\
&= \lim\limits_{\Delta t \to 0} 2t \frac{\Delta t}{\Delta t} = 2t
\end{align*}
$$

É simples (um pouco longo, via [binômio de Newton](https://pt.wikipedia.org/wiki/Bin%C3%B3mio_de_Newton#Nota%C3%A7%C3%A3o_e_f%C3%B3rmula)) demonstrar que, para uma função $f(t) = t^n$, temos que
$$
\frac{df}{dt} = \frac{d t^n}{dt} = n t^{n-1}
$$
que é o que costuma-se chamar de "regra do tombo", pois a derivada "tomba" o expoente $n$ e diminui-o por $1$. 
# Antiderivadas
Dada uma função $f(x)$, temos que sua **antiderivada** é uma outra função $F(x)$ que satisfaça
$$
\frac{dF}{dx} = f(x)
$$

Ou seja, é a "operação" oposta da derivada. 

Um exemplo usual é de que a posição é a antiderivada da velocidade, a velocidade é a antiderivada da aceleração, etc.

Note-se que tomar a antiderivada de $x^n$ é $\frac{x^{n+1}}{n+1}$, pois
$$
\frac{d}{dx}\frac{x^{n+1}}{n+1} = x^n
$$
e é o "inverso" da regra do tombo.
# Teorema Fundamental do Cálculo
O resultado basilar de Cálculo Diferencial e Integral é o Teorema Fundamental do Cálculo: fazer uma integral é tomar uma anti-derivada!
$$
\int_a^b f(x) dx = F(b) - F(a)
$$

Ou seja, derivada e integral são operações inversas umas às outras!
$$
\int_a^b \frac{df}{dx} dx = f(b) - f(a)
$$

# Exemplo: Movimento Uniformemente Variado (MUV)
Um corpo está em movimento uniformemente variado quando sua aceleração $a$ é constante. Como a aceleração é a derivada da velocidade
$$
\frac{dv}{dt} = a
$$
eu posso integrar essa equação para obter a velocidade do corpo[^5]
$$
\begin{align*}
v(t) - v(t_0) &= \int_0^t a \, d\tau = at\\
\therefore v(t) &= v_0 + at
\end{align*}
$$

Posso fazer a mesma coisa de novo: a velocidade é a derivada da posição[^6]
$$
\frac{ds}{dt} = v
$$
Integrando a equação novamente, e usando o resultado acima, obtemos
$$
\begin{align*}
s(t) - s(t_0) &= \int_0^t v(t) \, d\tau = v_0 t + \frac{at^2}{2}\\
\therefore s(t) &= s_0 + v_0 t + \frac{at^2}{2}
\end{align*}
$$

Ou seja, as equações básicas de cinemática que aprendemos no Ensino Médio requerem Cálculo para serem obtidas. Não caíram do céu! O $\frac{1}{2}$ não era ao acaso! E, de fato, este é o ponto: qualquer lei física que aprendemos na escola veio de alguma derivação matemática[^12]. 
# O que mais?
**2ª Lei de Newton**
$$
\vec{F} = \frac{d\vec{p}}{dt}
$$

**Equação de Euler-Lagrange (Mecânica Clássica)**
$$
\frac{d}{dt}\frac{\partial L}{\partial \dot{q}} = \frac{\partial L}{\partial q}
$$
**Equação de Onda**
$$
\frac{\partial^2 u}{\partial t^2} = c^2 \left(\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2}\right)
$$

**Equação de Schrödinger (Mecânica Quântica)**
$$
-\frac{\hbar^2}{2m} \frac{\partial^2 \psi}{\partial x^2} + V(x) \psi = i \hbar \frac{\partial \psi}{\partial t}
$$

**[Equação de Black-Scholes (Mercados financeiros)](https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_model#Black%E2%80%93Scholes_equation)**
$$
\frac{\partial V}{\partial t} + \frac{1}{2}\sigma^2 S^2 \frac{\partial^2V}{\partial S^2} + r S \frac{\partial V}{\partial S} - rV = 0
$$

...e por aí vai. Cálculo Diferencial e Integral é o bê-a-bá das Ciências Exatas como um todo; perguntar se cientistas utilizam Cálculo é tão esdrúxulo quanto perguntar se poetas usam palavras ou se biólogos usam a teoria de Darwin. É literalmente o capítulo 0 versículo 0, em particular, de todo o sucesso que a Física teve em explicar fenômenos tão drasticamente díspares quanto ondas gravitacionais e partículas elementares. Mas não tome minhas palavras com tanto peso; tome-as de um dos maiores matemáticos do século XX:
> "O Cálculo foi a primeira realização da matemática moderna, e é difícil superestimar sua importância. Creio que ele define, mais do que qualquer outra coisa, a concepção de matemática moderna; e o sistema de análise matemática, que é seu desenvolvimento lógico, ainda constitui o maior avanço técnico em pensamento exato."
> (John von Neumann)

Todo começo é difícil, mas a prática e a perseverança são fundamentais. Não consegui encontrar de qual autor eu li uma vez, num prefácio, que dizia que aprender Matemática requer uma leitura com lápis e papel sempre a postos. Isto é justamente o que torna as Ciências Exatas tão "precisas"[^7]: há conclusões que não são intuitivas, mas que são racionalmente deriváveis através de argumentos lógicos e bem delimitados; são conclusões, portanto, assertivas[^8]. Enfim, tudo para dizer que é importante não depender exclusivamente do que a intuição nos diz; muitas vezes é preciso sentar, pegar caneta e papel, e fazer contas, invés de lançar conjecturas infalseáveis sobre o mundo (como *muitos* fazem por aí...).

Matemática se assemelha muito à arte em vários aspectos, e não são poucos os matemáticos que submetem-se a tanta burocracia acadêmica puramente por este sentimento de beleza e de sublime que ela evoca. Inclusive, talvez como a arte, existe uma satisfação criadora em estudar Matemática (ou qualquer área correlata): quando demonstro algum resultado, por mais que ele tenha sido demonstrado originalmente[^9] há séculos ou milênios ou décadas atrás, estabeleço um vínculo com o problema; ele, de certa forma, torna-se meu, torna-se uma besta recém-domada; aquilo que era algo originalmente "impenetrável" torna-se, de certa forma, "meu", peculiarmente familiar e íntimo. 

Há, neste fazer, algo de ímpeto criador, pois demonstrações matemáticas, por mais que possuam "regras" bem delimitadas (referentes à Lógica Proposicional, em particular), não são algo que apreende-se puramente "de fora para dentro": Matemática é feita por outros seres humanos e, portanto, tanto parte de intuições que são intrinsecamente humanas quanto produz resultados que devem ser aferidos pela intuição humana[^10]; decorre que minha verdadeira compreensão de algum problema matemático [[O leitor lê um texto como quem decifra um enigma|requerem um envolvimento de minha parte]],  requerem que eu esteja ali "de corpo e alma" e que apreenda o problema de forma intuitiva (para mim) e lógica (para mim e pelo rigor do resultado). 

É algo desmoralizante quando nos introduzimos a alguém e ouvimos "nossa, eu odeio/odiava Física/Matemática na escola" ou "Física/Matemática é/era muito chato". É compreensível, pois o que somos ensinados na escola não é, em absoluto, parecido com o que estuda-se na faculdade (ainda mais para Matemática!). Nos últimos anos houve um *boom* de vídeos no YouTube, que buscam elucidar a paixão que é possível sentir pela Matemática. No âmago de quem trabalha com Matemática há uma alma curiosa e vivaz, que busca padrões que a Natureza aponta-nos, mas não concede-nos[^11].  

## Referências
- [3Blue1Brown: Calculus Playlist](https://www.youtube.com/playlist?list=PL0-GT3co4r2wlh6UHTUeQsrf3mlS2lk6x) é o santo Graal que muitos de nós (me incluo nisso) queríamos ter tido em nossos primeiros contatos com Cálculo. 3Blue1Brown foi um pioneiro fundamental no nicho de "animações matemáticas" do YouTube, e acredito que o ensino de Matemática como um todo está sob uma revolução há anos devido à sua influência e inspiração.
- STEWART, James. **Cálculo, Volume I**.
- GUIDORIZZI, Hamilton L. **Um curso de cálculo**. (Para os mais matematicamente inclinados/corajosos/curiosos; um paraíso para neurodivergentes excessivamente lógicos que odeiam fazer suposições sobre o por quê das coisas serem do jeito que são.)

[^1]: Leia-se: "conforme $x$ tende a $0$".
[^2]: A quem interesse: a animação foi feita com o pacote Manim, do Python, em particular o Manim *Community*. Para os códigos que utilizei, conferir [GitHub - nicholasvoltani/Manimations](https://github.com/nicholasvoltani/Manimations).
[^3]: Ao observador atento, pode-se perguntar "mas que ponto dentro do retângulo eu devo usar para medir a altura do respectivo retângulo?". Note que na animação, por exemplo, pega-se as alturas $f(x)$ dos pontos à esquerda dos retângulos. No fim das contas, não importa, pois estaremos tomando o limite em que "haverá somente uma altura" por retângulo. Inclusive, é por isso que é importante que a função a ser integrada **seja contínua**, pois é isso que assegura que *pontos próximos tenham alturas próximas*. [Porém...](https://www.youtube.com/watch?v=vUJEG3tUVaY)
[^4]: Em algum sistema de coordenadas, digamos, por exemplo, da esquerda para a direita, em metros.
[^5]: Assumindo que o movimento começa em $t_0 = 0$, por simplicidade, e definindo $v_0 \equiv v(t=0)$ e $s_0 \equiv s(t=0)$; o símbolo $\equiv$ denota a "definição" de alguma variável (no caso, $v_0$ e $s_0$). Supor $t_0 \neq 0$ faria surgir vários termos da forma $(t - t_0)$, e tornaria o exemplo mais opaco ao leitor mais leigo.
[^6]: \\begin{rant} Uso a variável $s$ para denotar posição somente para remeter às fórmulas que aprendemos na escola, pois acho péssimo utilizar $s$ para medir posição (em metros pelo SI), sendo que medimos tempo pela unidade de segundos $s$. Em nível universitário, geralmente usamos $x, y, z$ para denotar posições. \\end{rant}
[^7]: Até mesmo a noção de *probabilidade* é precisa neste sentido: é uma teoria que nasce da própria lógica matemática e não lhe é algo contingente. Ironicamente, por mais que probabilidades meçam incertezas, sua teoria é extremamente bem-conhecida e estudada ativamente, e empregada em situações em que existem incertezas em medições ─ ou seja, em quase todo lugar (*mileage may vary*)!
[^8]: Quando encontra-se um contra-exemplo de alguma conclusão lógica, revisa-se as hipóteses empregadas em sua formulação, e corrige-se de acordo. É como o famoso problema de ["todos os cisnes são brancos"](https://pt.wikipedia.org/wiki/Falseabilidade).
[^9]: Há muitos resultados que são redescobertos em vários momentos da História por pessoas diferentes, assim como resultados que são descobertos mas não publicamente, mas escute-me...
[^10]: Similarmente, [[Toda obra de arte é criada para outras pessoas]].
[^11]: Similarmente, [[A arte busca representar o mundo objetivo através de categorias humanas]].
[^12]: Dificilmente estudamos na escola alguma equação que foi formulada fenomenologicamente (ou seja, sem ser a partir de primeiros princípios) ─ se estudamos, geralmente é por fins históricos e a fim de demonstrar a generalidade de alguma outra lei que a substitua (por exemplo, [lei de Wien versus lei de Planck](https://pt.wikipedia.org/wiki/Lei_de_Wien#Dedu%C3%A7%C3%A3o)).