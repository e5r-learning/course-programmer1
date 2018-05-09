Curso "Programador Nível #1"
============================

> _by_ [**E5R Development Team**](@e5r), _author_ [**Erlimar Silva Campos**](@erlimar)

![](doc/course/assets/e5r_learning_course_programmer1.png)


## Público alvo

* Pessoas interessadas em iniciar no mundo do desenvolvimento de software mas que não tem nenhum conhecimento ainda.
* Programadores que já sabem alguma linguagem de programação mas que desejam revisar seus conhecimentos mais básicos.

## O que vou aprender?

Neste curso você aprenderá os conceitos mais básicos da programação, sem focar diretamente em uma linguagem específica,
mas passeando por várias delas para demonstrar os vários paradigmas da programação e como eles são aplicados nas linguagens
mais conhecidas do mercado.

Este curso é um pré-requisito para os cursos de "linguagens de programação".

## Conteúdo

* [Introdução](doc/course/intro.md)
* [Capítulo 1 - O "básico"](doc/course/chapter-01/intro.md)
  - [O mundo dos computadores](doc/course/chapter-01/computers.md)
  - [Os programas de computador](doc/course/chapter-01/programs.md)
* [Capítulo 2 - As "linguagens"](doc/course/chapter-02/intro.md)
  - [Tipos de linguagens de programação](doc/course/chapter-02/types-languages.md)
  - [Paradigmas das linguagens de programação ](doc/course/chapter-02/paradigms.md)
* Capítulo 3 - A dinâmica de um programa
  - EntryPoint e a "main" function
    - Falar sobre: não importa se é um sistema web, um console ou um jogo. Tudo começa em algum lugar
    - O que importa é entender, que uma vez chegando "ali", você direciona o programa para onde quiser
    - Ex:
      - C/C++/C#/Java Main
      - Web Site/Front JavaScript: qualquer linha executável na ordem escrita vs document.load
      - Web Site/Back PHP, C# MVC, Global.asax, Owin. NodeJS express route
  - Os fluxos de decisão
  - Os fluxos de repetição
  - Os fluxos de saltos (chamadas) de programas
    - O famigerado GOTO que mudou de nome para Thy/Catch
      - C, Batch, Pascal, Alguma linguagem moderna
    - JavaScript: call, apply e bind
    - Assembly JUMP
    - Dinâmica da Pilha
  - Heap (lembra da Pilha?)
    - O odiado ponteiro do C
    - malloc, calloc, realloc, e free
    - GC (Garbage Collector) e a farça de que não precisamos controlar a memória
      - E quem vai escrever os GC's? Citar evolução dos GC's para Java e .NET, explicando que alguém teve
        de escrever eles, e foi um programador
* Capítulo 4 - De cliente/servidor para Web e o "Multiplataforma"
  - Explicar porque não existe a "programação web" e "programação desktop"
  - A rede, o TCP/IP, o Socket e o HTTP
  - Multiplataforma: Linux, macOS, Windows
  - Programas multiplataforma e as diretivas de compilador
    - C/C++/C# #if DEBUG - #ifdef
    - C# Environment
    - Delphi/Pascal {$DEFINE} {$IFDEF}
    - Python import os, NodeJs require('os')
    - Java System.getProperty
* Capítulo 5 - Compartilhamento e Modularização
  - Módulos, pacotes
  - using, import, #include, require require_once
  - package managements e os repositórios de pacotes
  - versões e versionamento
    - SemVer