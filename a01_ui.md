---
title: "Introdução à Organização de Computadores." # Titulo
format:
  html:
      toc: true # tabela de conteúdo
      toc-title: "Tópicos"
      toc_float: true #tabela flutuante
      theme: 
        - simplex # Tema do bootwatch
        - custom_callouts.scss
---


# 1.  Encontre um Chef que saiba de receitas.
Imagine que você é o dono de um restaurante e possui uma quantidade importante de receitas, porém você não e chef de cozinha e precisará de alguém com o conhecimento necessário para poder executar as suas receitas, bom esse chef é o seu computador e as receitas todas aquelas instruções que daremos ao computador utilizando uma **Lógica de Programação.**

Os componentes do computador (Sistema computacional) serão descritos a continuação e compreendem:

- Hardware
  - Entrada
  - Unidade Central de Processamento (CPU)
    - Unidade de Lógica e Aritmética (ULA)
    - Unidade de Controle (UC)
  - Memória
  - Saída

- Software


## 1.1. Entrada, Saída e Memória

**Entradas e saídas, Input/Output ou simplesmente IO:** São os *hardwares* (Equipamentos físicos) responsáveis por captar os dados (no caso das entradas) e apresentar esses dados transformados (no caso das saídas). Se pensarmos esses conceitos dentro da mesma lógica do cozinheiro, podemos entender as Entradas como os sentidos do corpo humano e a saída como as extremidades e formas de se comunicar com os ajudantes de cozinha.

Uma vez esses dados são captados serão armazenados junto aos programas na **Memória**, existem dois tipos: memória principal e memória secundaria, a primeira fornece o necessário para transformar os dados de entrada em dados de saída (Ex. memoria RAM e ROM) a segunda guarda os dados e os recupera novamente após desligar o seu aparelho (Ex. HD), também podem ser consideradas como um dispositivo IO quando os dados são carregados a partir dela ou gravados nela.

## 1.2. CPU

**ULA:** É o local onde ocorrem as operações como adição, subtração, multiplicação e divisão (Aritmética), bem como operações lógicas (AND, OR e NOT). Realizando essas operações em alta velocidade, permite que  a UC possa executar as instruções do programa  de forma eficiente. 

**UC:**  Implementa um conjunto de instruções  e controla os demais componentes, essas instruções encontrasse na memória. Então, aplicando isso em nossa analogia do chef cozinha, a UC equivale ao sistema nervoso que executa pensamentos do cérebro (Memória) de nosso personagem.  

## 1.3. Software
Toda essa informação flui pelos componentes em uma serie de zeros e um, imagina termos que dar instruções ao nosso computador por números binários!, para digitar em hexadecimal o ano de 1990 precisaria escrever em números binário do seguinte jeito: **0001100110010000**, conhecido como **binary digit (bit)** ; os softwares nos permitem interagir com o sistema computacional sem precisar escrever instruções por **bits.** Os três principais tipos de software são:

- **De sistema:** Nesta categoria encontram-se os sistemas operativos (OS), BIOS e drivers. É o conjunto de programas que permitem que o computador funcione corretamente e forneça um meio de se comunicar (interface) para o usuário interagir com ele. 

- **De aplicação:** É um tipo de software projetado para atender as necessidades específicas de um usuário ou grupo de usuários, temos exemplos amplamente conhecidos como os navegadores, Aplicativos de office e os app em nossos smartphone.

<!-- Callout sobre diferenças entre aplicação (Aplicativos) e programa. 
|Título: Aplicativos ou programas| 
-->

- **De serviço:** Também conhecidos como aplicativos web, são programas que podem ser utilizados diretamente na Internet, sem necessidade de instalação em um sistema computacional, por meio de um navegador. A plataforma de treinamento que você está utilizando em este momento (Moodle) é um software de serviço.

No final os software dão sentido para nós sobre as funções dos componentes embutidos em um processador de dados.

<!--
> Recursos 

# Callout nativos

::: callout-note
Note that there are five types of callouts, including:

`note`, `warning`, `important`, `tip`, and `caution`.
:::

::: callout-important
Note that there are five types of callouts, including:

`note`, `warning`, `important`, `tip`, and `caution`.
:::

::: callout-warning
Note that there are five types of callouts, including:

`note`, `warning`, `important`, `tip`, and `caution`.
:::

::: callout-tip
## Tip With Caption

This is an example of a callout with a caption.
:::

::: callout-bug
## Bug With Caption

This is an example of a callout with a caption.
:::

::: callout-question
## Question With Caption

This is an example of a callout with a caption.
:::

::: callout-example
## Exemple With Caption

This is an example of a callout with a caption.
:::

::: {.callout-caution collapse="true"}
## Expand To Learn About Collapse

This is an example of a 'folded' caution callout that can be expanded by the user. You can use `collapse="true"` to collapse it by default or `collapse="false"` to make a collapsible callout that is expanded by default.
:::

Pode aplicar o formato expandible nos outros tipos de call out 

# Callouts Personalizados:

::: {.callout-objetivo .icon .callout-note collapse="true"}
Callout objetivo
:::

::: {.callout-quotes .icon}
Notas e definições.
:::

::: {.callout-fig .icon .callout-note collapse="true"}
Imagens 
:::

::: {.callout-exp .icon}
Fatos científicos, experiencias
:::

:::{.callout-ref .icon .callout-note collapse="true"}
## Referências e leitura recomendada
- **Referências**

Fontes utilizadas

- **Leitura recomendada**

Livros e artigos para aprofundar nos conceitos
:::


# Instruções para exportar o html:

1. apos editar o .Rmd, .Qmd ou .md publique no Rpub

2. abra o R pub e com click secundario em; This frame > Show only tgis frame

3. Click secundario > Save Page as... -->

