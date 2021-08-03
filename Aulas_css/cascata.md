# A cascata (cascading)

A escolha do broswer de qual regra aplicar, caso haja muitas regras para o mesmo elemento.

* Seu estilo é lido de cima para baixo.

É levado em consideração 3 fatores. 

1- Origem do estilo
2- Especificidade
3- Importância


# A origem do Estilo 

A regra que vem primeiro e : 

inline > tag style > tag link


# A regra !important

* Cuidado evite o uso
* Não e considerado uma boa prática
* Quebra o fluxo natural da cascata.


# A especifidade 

É um cálculo matemático, onde, cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

0-    Universal selector, combinators e negation pseudo-class (:not())
1-    Element type selector e pseudo-elements(::before, ::after)
10-   Classes e attribute selectors
100-  ID selector
1000- Inline
