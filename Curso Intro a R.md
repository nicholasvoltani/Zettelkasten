---
Date: 2023-01-10
Tags: literature/lecture
---
up:: 

# Aula 1
## Objetos vazios
- `NA`: dado faltante
- `NAN`:
- `NULL`:
- 

## Análise básica de dados
- `str`: descrição breve, com alguns casos de valores
- `summary`: min/max/median/mean etc
- `Ctrl + Shift + C`: comenta linha

---
# Aula 2: Tipos de Dados em R
## Instalando/usando bibliotecas
- `install.packages("...")` (precisa estar **"entre aspas"**)
- `library(...)` (**não** precisa estar entre aspas)

## Dialetos de manipulação de dados
- **R-Base**
- **Tidyverse**: legibilidade / interfaces com SQL e Spark
- **Data.table**: sintaxe mais concisa / melhor para performance com tabelas grandes

## Manipulação de tabelas
- tidyverse
	- `slice`: linhas?
	- `select`: colunas?

## Tipos de dados (como o R armazena, low-code)
- **Categórico: Qualitativo**
	- Nominal (sem ordem):
		- Character `chr`: string básico
		 -  Factor `fct`: string *restrito* (`categorical` no Pandas)
	 - Ordinal (com ordem):
		- Ordered `ord`: **factor** ordenado
		- Date `date`
	- Lógica
		- `lgl`
- **Numérico: Quantitativo**
	- Contínuo
		- Double `dbl`
	- Discreto
		- `int`

## Hierarquia de Coerção de **tipos de dados** no R (classes)
Como o R armazena os dados, low-code.
- character
- complex
- double
- integer
- logical
- raw (bytes)

## Colunas têm mesmo tipo para todo elemento
- `c(1, 2, 3, 4)`: tipo `int`
- `c(1, 2, 3, "4")`: tipo `chr`
	- vai se tornar `c("1", "2", "3", "4")`

## Conferindo o tipo do objeto no R
- `class(obj)`: classe mais genérica
	- `class(1)` = **numeric**
	- `class(1.2)` = **numeric**
	- `class("blah")` = **character**
	- `class(TRUE)` = **logical**
- `typeof(obj)`: instância particular do objeto[^1]
	- `typeof(1)` = **double**
	- `typeof(as.integer(1))` = **integer**
	- `typeof("blah")` = **character**
	- `typeof(TRUE)` = **logical**

## Estruturas de Dados em R
![[Pasted image 20230117192610.png]]

PS: `tibble`s funcionam como Dataframes otimizados!

### Vetores
`c(...)`

---
# Aula 3 (Atributos, Factors, Dataframes)
## Atributos de objetos
`attributes` verifica quais os atributos de um objeto.

- `names(...)`: dá nomes de colunas
	- Também serve `colnames(...)`
- `row.names(...)`: dá nome das linhas (para `data.frame`s)
	- Também `rownames(...)`

## Fatores: vetores com categóricos
- `levels`: dá um "unique" dos elementos do vetor
- Transforma em ordinais com `ordered`
	- **Como definir (relação de) ordem arbitrariamente?** `forcats` deixa mais simples:

## Datas
- `as.Date`
- Subtração de `date`s é dias

## Sintaxes diferentes datatable
![[Pasted image 20230117205040.png]]

---
# Aula 4: Manipulação de Dados (Tidyverse)
![[Pasted image 20230119192950.png]]

## Tidyverse: 
![[Pasted image 20230119193531.png]]

1. **Importação**
	- `readr`
2. **Tidy**
	- `tidyr`]
3. **Transformar**
	- `dplyr`
4. **Visualização**
	- `ggplot` (*graph grammar*)
5. **Modelar**
	- `tidymodels`
6. **Comunicar**
	- `rmarkdown`

## Tidy data
![[Pasted image 20230119194421.png]]

### Workflow de Análise
**Já carregados no tidyverse**
- `readr`
- ==`tibble` (df's automatizados)==
- `tidyr` (reformula layout de dados)
- `dplyr` 
- `ggplot2`
- `purrr` programação funcional
- `forcats` operações com categóricos
- `stringr` operações com strings

**Pertencem, mas não carregam automaticamente com tidyverse**
- `knitr`
- `lubridate`
- `haven` ler SAS, SPSS etc
- `broom`
- `rmarkdown`

## Exploração de Dados
**Visualização**
- `glimpse`
  ![[Pasted image 20230119204025.png]]
- `str`
  ![[Pasted image 20230119204036.png]]

**Manipulação**
- `filter`
- `mutate`
	- `ifelse(logical_condition, true_result, false_result)`
-  `arrange` (**sort**)
	- `arrange(col1, desc(col2), etc)`
	- Pode fazer `arrange(-num_col)` como shorthand para `desc(any_type_col)`

**Seleção de linhas**
- `select` (colunas)
	- `select(-c(col1, col2))` (`-` serve para **desconsiderar** colunas)
	- `slice` (linhas)
	- `slice_max(col)` / `slice_min(col)`
	- `top_n(num, col)`

**Group_by**
- `group_by`
- `summarise`
	- `new_col = n()`: counts rows
	- `new_col2 = n_distinct(example_col)`
	- `new_col3 = sd(varX, na.rm = TRUE`

**Colunas compostas**
- `separate(orig_col, into=COLS, sep=..., remove=BOOL_REMOVE_ORIGINAL_COL)`
- `unite(COLS, col=NEW_COL, sep=..., remove=BOOL_REMOVE_ORIGINAL_COLS)` (ótimo para criar **chaves**!)

**Lidando com múltiplas colunas com mesmo cálculo**
- `across`
  ![[Pasted image 20230122160221.png]]


# Aula 5
## `tidyr::unnest`
- `Starwars %>% select(name, films) %>% unnest` (coluna `films` é, em geral, listas)

## `tidyr::nest`
- `df %>% nest(col1:coln)` (útil para caso **cada observação possui várias informações**)
	- cada linha possui um `df / tbl`

## Não podemos fazer média de colunas de tibbles
- Uma coluna de um `tibble` é também um `tibble`
	- Agregar `tibbles`: `%>% summarise`
	- Para usar uma função direto, podemos usar `tb %>% pull(col)` (converte em vetor) `%>% mean/etc`

# Aula 6 - Última aula
## Forcats: trabalhando com `factors`
- `fct_rev`
- `fct_shift` (como numa esteira)
- `fct_reorder(col_to_be_reordered, col_which_gives_order)`
	- Parece ser bem útil para plots, boxplots, etc
- `fct_lump_min(factors, min_threshold, ...)`: agrega casos menos frequentes em uma categoria default (`"other"`)

## Stringr: facilitador de RegEx
- `str_count(string, pattern` => `str_count("AAaA", "A") == 4`
- `str_replace(strings, pattern, replacement)` (troca **o primeiro caso**)
	- `str_replace_all(strings, pattern, replacement)` (troca **todos** matches)
- `str_match`

## Ggplot
![[Pasted image 20230126195826.png]]
- `ggplot()`: cria o canvas inicial
- `dataframe %>% ggplot()` dá os dados
- `dataframe %>% ggplot() + aes(x=col_x, y=col_y)` preenche a **estética** do gráfico (seus **eixos**)
- `dataframe %>% ggplot() + aes(x=col_x, y=col_y) + geom_...` descreve a **geometria** do gráfico
	- `geom_boxplot()`
	- `geom_point()` scatterplot
	- `geom_col()` bar graph

**De baixo para cima:**
![[Pasted image 20230126195538.png]]

## Mais recursos
- `skimr`: resuminhos MUITO bons! Até mini-histogramas de colunas!
- `janitor::clean_names`: redefinir nomes de colunas (lowercase, sem whitespace, etc)!
- `FlexDashboard`: criar dashboards a partir de RMarkdown

# Último quiz
- `~ sum(.x)` é equivalente a `function(.x) {sum(.x)}`

## GGplot bars
- `geom_bar(position=`
	- ` ="stack")` : gráfico com legenda "stacked"
	- ` ="dodge")` : gráfico com legenda "lado a lado"
	- ` ="fill")` : gráfico com legenda "stacked 100%"


---
### Referências
- **Referência das referências**: https://paulvanderlaken.com/2017/08/10/r-resources-cheatsheets-tutorials-books/#cheatsheet

- **Livros**
	- **Os Mandamentos de Yours Truly**
		- **R for Data Science**, ==Hadley Wickham== & Jessica: https://r4ds.had.co.nz/introduction.html
		- **Advanced R**, Hadley Wickham: http://adv-r.had.co.nz/Introduction.html
	- **# Feature Engineering and Selection: A Practical Approach for Predictive Models**, Max Kuhn e Kjell Johnson http://www.feat.engineering/
	- **# Fundamentals of Data Visualization**, Claus Wilke: https://clauswilke.com/dataviz/introduction.html
		- **Getting things in the right order**, Claus Wilke https://wilkelab.org/SDS375/slides/getting-things-in-order.html#1

- **Escolhendo gráficos para visualização de dados**: https://www.data-to-viz.com/

- **Cursos**
	- https://curso-r.com/
	- https://swirlstats.com/

- https://www.youtube.com/@PraticadeDados
- https://beatrizmilz.github.io/aMostra-IME-2019-DataVis/#1
- https://rladies.org/


[^1]: Na prática, `typeof` só é diferente de `class` para números: ambos `integer` e `double` são da classe `numeric`.
