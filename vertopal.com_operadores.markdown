---
jupyter:
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
  language_info:
    codemirror_mode:
      name: ipython
      version: 3
    file_extension: .py
    mimetype: text/x-python
    name: python
    nbconvert_exporter: python
    pygments_lexer: ipython3
    version: 3.10.6
  nbformat: 4
  nbformat_minor: 2
  orig_nbformat: 4
  vscode:
    interpreter:
      hash: 916dbcbb3f70747c44a77c7bcd40155683ae19c65e1c03b4aa3499c5328201f1
---

::: {.cell .markdown}
# Operadores

Na programação, operadores são símbolos que instruem o interpretador a
realizar manipulações matemáticas, lógicas e de comparação específicas.
Portanto, podemos utilizar operadores para auxiliar ou resolver qualquer
lógica exigida no código. A seguir, vamos explorar quais operadores
existem em Python.
:::

::: {.cell .markdown}
# 1. Operadores aritméticos. {#1-operadores-aritméticos}

Assim como na matemática, podemos realizar operações de soma, subtração,
divisão e outras. Em Python, também temos essa possibilidade de realizar
diversas operações. Essas operações são essenciais para realizar
cálculos e manipulações matemáticas em programas.

Abaixo está a tabela com todos os operadores disponíveis.

  ---------------------------------------------------------------------------
  Operador        Símbolo   Descrição
  --------------- --------- -------------------------------------------------
  Adição          \+        Realiza a adição de dois valores ou concatenação
                            de duas sequências.

  Subtração       \-        Realiza a subtração de dois valores.

  Multiplicação   \*        Realiza a multiplicação de dois valores ou
                            duplica uma sequência.

  Divisão         /         Realiza a divisão de dois valores.

  Divisão inteira //        Realiza a divisão de dois valores e retorna a
                            parte inteira do resultado.

  Resto da        \%        Retorna o resto da divisão entre dois valores.
  divisão                   

  Exponenciação   \*\*      Realiza a exponenciação de um valor pelo outro.
  ---------------------------------------------------------------------------
:::

::: {.cell .markdown}
```{=html}
<h5>Nesse primeiro exemplo realizaremos a Adição e a Subtração deles. </h5>
```
Dica: A função \"print()\" é utilizada para exibir textos que auxiliam
no entendimento do conteúdo. O resultado da operação será exibido na
linha seguinte. Nos exemplos a seguir, utilizaremos os números 5 e 2.
:::

::: {.cell .code execution_count="1"}
``` python
print("Resultado da Adição: ");
print ( 5 + 2 )


print("Resultado da Subtração: ");
print ( 5 - 2 )
```

::: {.output .stream .stdout}
    Resultado da Adição: 
    7
    Resultado da Subtração: 
    3
:::
:::

::: {.cell .markdown}

------------------------------------------------------------------------
:::

::: {.cell .markdown}
```{=html}
<h5>Agora teremos a multiplicação, divisão e exponenciação. Bem simples, não é? </h5>
```
:::

::: {.cell .code execution_count="2"}
``` python
print("Resultado da Multiplicação: ")
print ( 5 * 2 )


print("Resultado da Divisão: ")
print ( 5 / 2)


print("Resultado da Exponenciação: ")
print (5 ** 2)
```

::: {.output .stream .stdout}
    Resultado da Multiplicação: 
    10
    Resultado da Divisão: 
    2.5
    Resultado da Exponenciação: 
    25
:::
:::

::: {.cell .markdown}

------------------------------------------------------------------------
:::

::: {.cell .markdown}
```{=html}
<h5>Vejamos o restante das operações.</h5>
```
:::

::: {.cell .code execution_count="3"}
``` python
print("Resultado da Divisão Inteira: ")
print ( 5 // 2)

print("Resultado do Resto da divisão: ")
print ( 5 % 2)
```

::: {.output .stream .stdout}
    Resultado da Divisão Inteira: 
    2
    Resultado do Resto da divisão: 
    1
:::
:::

::: {.cell .markdown}

------------------------------------------------------------------------
:::

::: {.cell .markdown}
```{=html}
<h5>Assim como seu professor te mostrou no ensino fundamental, é possível definir uma ordem de execução nas operações e no Python também é possível fazer isso da mesma forma, utilizando parenteses na operação que desejamos que seja prioridade.Vejamos as diferenças no exemplo abaixo.</h5>
```
:::

::: {.cell .code execution_count="4"}
``` python
print ("Resultado ANTES de definir uma ordem de prioridade: ")
print ( 5 + 2 * 4 )


print ("Resultado APÓS definir uma ordem de prioridade: ")
print ( (5 + 2) * 4 )
```

::: {.output .stream .stdout}
    Resultado ANTES de definir uma ordem de prioridade: 
    13
    Resultado APÓS definir uma ordem de prioridade: 
    28
:::
:::

::: {.cell .markdown}
Isso acontece pois ANTES de definir a prioridade, é primeiro realizado a
multiplicação 2 \* 4, e APÓS a definição, a soma 5 + 2 foi a primeira a
ser realizada.\
\_\_\_\_\_\_

```{=html}
<h5>Conclusão do Capítulo</h5>
```
Neste tópico conseguimos visualizar um exemplo de todas as operações
aritméticas possíveis de serem realizadas e também como conseguimos
definir uma prioridade pra elas de forma que seja possível decidir em
que ordem ela será executada.
:::

::: {.cell .markdown}

------------------------------------------------------------------------
:::

::: {.cell .markdown}
# 2. Operadores de atribuição. {#2-operadores-de-atribuição}

Os operadores de atribuição atribuem valor a uma variável e também podem
acrescentar ou diminuir valores dessa atribuição, veja alguns exemplos
de atribuidores abaixo.

  ---------------------------------------------------------------------------
  Operador        Símbolo   Descrição
  --------------- --------- -------------------------------------------------
  Atribuição      =         Atribui um valor a uma variável.

  Adição e        +=        Realiza a adição entre duas variáveis e atribui o
  atribuição                resultado à primeira.

  Subtração e     -=        Realiza a subtração entre duas variáveis e
  atribuição                atribui o resultado à primeira.

  Multiplicação e \*=       Realiza a multiplicação entre duas variáveis e
  atribuição                atribui o resultado à primeira.

  Divisão e       /=        Realiza a divisão entre duas variáveis e atribui
  atribuição                o resultado à primeira.

  Divisão inteira //=       Realiza a divisão inteira entre duas variáveis e
  e atribuição              atribui o resultado à primeira.

  Resto da        %=        Calcula o resto da divisão entre duas variáveis e
  divisão e                 atribui o resultado à primeira.
  atribuição                

  Exponenciação e \*\*=     Realiza a exponenciação entre duas variáveis e
  atribuição                atribui o resultado à primeira.
  ---------------------------------------------------------------------------
:::

::: {.cell .markdown}
Atribuição de variáveis talvez seja uma das funcionalidades mais
utilizadas em Python e talvez uma das mais importantes dentro da
programação. Veja como fazer isso no exemplo abaixo.
:::

::: {.cell .code execution_count="5"}
``` python
numero = 5  #Definindo que a variável "numero" vale 5
print ( numero ) 
```

::: {.output .stream .stdout}
    5
:::
:::

::: {.cell .markdown}
Nesse exemplo acima, nós indicamos que a variável \"numero\" possuí um
valor de 5

------------------------------------------------------------------------
:::

::: {.cell .markdown}
E se atribuissemos o valor de 2 para a mesma variável?
:::

::: {.cell .code execution_count="6"}
``` python
numero +=2
print ( numero ) 
```

::: {.output .stream .stdout}
    7
:::
:::

::: {.cell .markdown}
Como esperado, ocorreu uma adição na variável \"numero\" com os valores
estabelecidos. \_\_\_\_\_\_ Mas e se subtraissemos, multiplicassemos ou
dividissemos?
:::

::: {.cell .code execution_count="7"}
``` python
numero -=2 
print("Resultado da subtração: ")
print ( numero ) 


numero *=2
print("Resultado da multiplicação: ")
print ( numero )


numero /=2
print("Resultado da divisão: ")
print ( numero )
```

::: {.output .stream .stdout}
    Resultado da subtração: 
    5
    Resultado da multiplicação: 
    10
    Resultado da divisão: 
    5.0
:::
:::

::: {.cell .markdown}
```{=html}
<h5>Veja o resultado com a atribuição das operações de resto, divisão inteira e exponenciação</h5>
```
:::

::: {.cell .code execution_count="8"}
``` python

numero %= 2
print ("Resultado do resto da divisão: ")
print ( numero )

numero = 5
numero //=2
print ("Resultado da divisão inteira: ")
print ( numero )

numero = 5
numero **=2
print ("Resultado da exponenciação: ")
print ( numero )
```

::: {.output .stream .stdout}
    Resultado do resto da divisão: 
    1.0
    Resultado da divisão inteira: 
    2
    Resultado da exponenciação: 
    25
:::
:::

::: {.cell .markdown}
```{=html}
<h5>Conclusão do capítulo</h5>
```
:::

::: {.cell .markdown}
# 3.Operadores de comparação. {#3operadores-de-comparação}

Operadores de comparação em Python são utilizados para comparar valores
e retornar um resultado booleano (verdadeiro ou falso) com base na
comparação realizada. Eles normalmente são muito utilizados com
estruturas condicionais.
:::

::: {.cell .markdown}
  --------------------------------------------------------------------------
  Operador    Símbolo   Descrição
  ----------- --------- ----------------------------------------------------
  Igual a     ==        Verifica se dois valores são iguais.

  Diferente   !=        Verifica se dois valores são diferentes.
  de                    

  Maior que   \>        Verifica se o valor da esquerda é maior que o valor
                        da direita.

  Menor que   \<        Verifica se o valor da esquerda é menor que o valor
                        da direita.

  Maior ou    \>=       Verifica se o valor da esquerda é maior ou igual ao
  igual a               valor da direita.

  Menor ou    \<=       Verifica se o valor da esquerda é menor ou igual ao
  igual a               valor da direita.
  --------------------------------------------------------------------------
:::

::: {.cell .markdown}
Vamos utilizar um exemplo culinário, vejamos.

Supondo que temos dois clientes e eles querem criar um código em python
para comparar suas pizzas e saber se elas são as mesmas, para fazer tal
código, será necessário utilizar o operador \"Igual a\"
:::

::: {.cell .code execution_count="9"}
``` python
#  Definindo o sabor da pizza do primeiro cliente
pizza_1 = "Frango com Catupiry"
#  Definindo o sabor da pizza do segundo cliente
pizza_2 = "Calabresa"

#  Realizando a comparação das pizzas 
pizza_1 == pizza_2
```

::: {.output .execute_result execution_count="9"}
    False
:::
:::

::: {.cell .markdown}
Após a realização da comparação, os clientes puderam ter certeza de que
a verificação de que suas pizzas eram iguais, resultou em \"Falsa\".
\_\_\_\_\_\_\_\_\_\_\_

Mas e se afirmassemos que suas pizzas são diferentes? para isso
precisaremos utilizar o operador \"Diferente de\" cujo simbolo é \"!=\"
:::

::: {.cell .code execution_count="10"}
``` python
#  Definindo o sabor da pizza do primeiro cliente
pizza_1 = "Frango com Catupiry"
#  Definindo o sabor da pizza do segundo cliente
pizza_2 = "Calabresa"

# Realizando a comparação das pizzas
pizza_1 != pizza_2
```

::: {.output .execute_result execution_count="10"}
    True
:::
:::

::: {.cell .markdown}
Com essa comparação eles puderam ter a certeza de que suas pizzas são
diferentes pois o resultado da comparação retornou \"True\"
\_\_\_\_\_\_\_\_\_\_\_
:::

::: {.cell .markdown}
Nosso cliente também está interessado em saber sobre os preços, e está
tentando criar um script para verificar qual preço é menor ou maior,
para isso ele precisará utilizar outros operadores de comparação.

Vamos dizer que a pizza de Calabresa custa R\$30.00 e a pizza de Frango
custa \"R\$35.00

No código abaixo, iremos verificar se o valor da pizza de frango é MAIOR
que a de calabresa.
:::

::: {.cell .code execution_count="11"}
``` python
pizza_calabresa = 30.00
pizza_frango = 35.00

pizza_frango > pizza_calabresa
```

::: {.output .execute_result execution_count="11"}
    True
:::
:::

::: {.cell .markdown}
Com essa comparação, é possível inferir que a Pizza de frango custa mais
do que a de calabresa. \_\_\_\_\_\_ Mas e se quisessemos um retorno
verdadeiro de qual pizza tem o menor valor? Ai teriamos que usar o
operador \"Menor que\" cujo simbolo é \"\<\"

Por exemplo.
:::

::: {.cell .code execution_count="13"}
``` python
pizza_calabresa = 30.00
pizza_frango = 35.00

pizza_calabresa < pizza_frango
```

::: {.output .execute_result execution_count="13"}
    True
:::
:::

::: {.cell .markdown}
Basicamente acabamos de dizer: \"O valor da pizza de calabresa é MENOR
QUE o da pizza de frango\" e seu retorno \"True\" significa que a
comparação foi bem-sucedida. \_\_\_\_\_\_
:::

::: {.cell .markdown}
Temos outros comparadores que possuem essa mesma função porém com um
adicional, eles além de verificar se é MAIOR ou MENOR, eles verificam
também se o valor é IGUAL.

Por exemplo, vamos dizer que o cliente não tem certeza se a pizza de
Frango possui um valor maior ou igual a pizza de Calabresa e ele deseja
um códígo que faça essa verificação, veja abaixo.
:::

::: {.cell .code execution_count="14"}
``` python
pizza_calabresa = 30.00
pizza_frango = 35.00

pizza_frango >= pizza_calabresa
```

::: {.output .execute_result execution_count="14"}
    True
:::
:::

::: {.cell .markdown}
Dizendo que \"A Pizza de frango possui um valor MAIOR ou IGUAL que a
pizza de calabresa\" tivemos um retorno verdadeiro. \_\_\_\_\_ Mas e o
contrário, como seria a verificação se o cliente quisesse saber se o
valor da pizza é MENOR ou IGUAL? Ai teriamos que usar esse código:
:::

::: {.cell .code execution_count="15"}
``` python
pizza_calabresa = 30.00
pizza_frango = 35.00

pizza_frango <= pizza_calabresa
```

::: {.output .execute_result execution_count="15"}
    False
:::
:::

::: {.cell .markdown}
Nesse caso tivemos um retorno de \"False\", pois a pizza de frango não
possui valor MENOR ou IGUAL a pizza de calabresa.
:::

::: {.cell .markdown}
# 4.Operadores lógicos. {#4operadores-lógicos}
:::

::: {.cell .markdown}
  ------------------------------------------------------------------------------
  Operador   Símbolo   Descrição
  ---------- --------- ---------------------------------------------------------
  E lógico   and       Retorna True se ambas as expressões booleanas forem
                       verdadeiras.

  OU lógico  or        Retorna True se pelo menos uma das expressões booleanas
                       for verdadeira.

  NÃO lógico not       Inverte o valor booleano de uma expressão.
  ------------------------------------------------------------------------------
:::

::: {.cell .markdown}
Agora nós temos uma missão, o cliente deseja comprar pizzas variadas e
precisamos fazer uma verificação para saber se temos essas pizzas à
disposição. E para isso iremos utilizar operadores lógicos

Nesse primeiro momento, ele deseja comprar duas pizzas, uma de calabresa
e outra de frango.
:::

::: {.cell .code execution_count="19"}
``` python
Pizza_Calabresa = True
Pizza_Frango = True

print(Pizza_Calabresa and Pizza_Frango)
```

::: {.output .stream .stdout}
    True
:::
:::

::: {.cell .markdown}
Ambas pizzas estão disponíveis, então o retorno \"True\" indica que
temos tudo que precisamos para criar a pizza. \_\_\_\_\_

Mas e se uma pizza não puder ser feita?
:::

::: {.cell .code execution_count="20"}
``` python
Pizza_Calabresa = False
Pizza_Frango = True

print(Pizza_Frango and Pizza_Calabresa)
```

::: {.output .stream .stdout}
    False
:::
:::

::: {.cell .markdown}
Como a pizza de calabresa não está disponível, o operador AND não pode
ser satisfeito, retornando assim \"False\" para a verificação lógica.
\_\_\_\_\_\_

Digamos que agora nosso cliente quer comprar apenas UMA pizza e tanto
faz se a pizza de Frango está disponível OU se é a de Calabresa, ele
gosta de ambas. Para isso, é possível utilizar o operador \"OU\"
:::

::: {.cell .code execution_count="21"}
``` python
Pizza_Calabresa = False
Pizza_Frango = True

print(Pizza_Frango or Pizza_Calabresa)
```

::: {.output .stream .stdout}
    True
:::
:::

::: {.cell .markdown}
Foi constatada que a pizza de Frango está disponível, sendo assim
possível realizar a compra.
:::

::: {.cell .markdown}
# 5.Operadores identidade. {#5operadores-identidade}
:::

::: {.cell .markdown}
  ---------------------------------------------------------------------------
  Operador     Símbolo   Descrição
  ------------ --------- ----------------------------------------------------
  É            is        Retorna True se as duas variáveis referenciarem o
                         mesmo objeto na memória.

  Não é        is not    Retorna True se as duas variáveis referenciarem
                         objetos diferentes na memória.
  ---------------------------------------------------------------------------
:::

::: {.cell .markdown}
```{=html}
<h4>Por exemplo</h4>
```
:::

::: {.cell .markdown}
# 6.Operadores de associação. {#6operadores-de-associação}
:::

::: {.cell .markdown}
  ---------------------------------------------------------------------------
  Operador     Símbolo   Descrição
  ------------ --------- ----------------------------------------------------
  Pertence a   in        Retorna True se um valor estiver presente em uma
                         sequência.

  Não pertence not in    Retorna True se um valor não estiver presente em uma
  a                      sequência.
  ---------------------------------------------------------------------------
:::

::: {.cell .markdown}
```{=html}
<h4>Por exemplo</h4>
```
:::

::: {.cell .code}
``` python
```
:::

::: {.cell .code}
``` python
```
:::
