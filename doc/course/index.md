# Conteúdo

* [Introdução](intro.md)
* [Capítulo 1 - O "básico"](chapter-01/intro.md)
  - [O mundo dos computadores](chapter-01/computers.md)
  - [Os programas de computador](chapter-01/programs.md)
  - [O formato binário](chapter-01/bin.md)
  - [O compilador](chapter-01/compiler.md)
* [Capítulo 2 - As "linguagens"](chapter-02/intro.md)
  - [Tipos de linguagens de programação](chapter-02/types-languages.md)
  - [Paradigmas das linguagens de programação ](chapter-02/paradigms.md)
* Capítulo 3 - A dinâmica e estrutura de um programa
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
* Capítulo 4 - Funções, procedimentos, parâmetros e retorno
  - Function retorna
    - JavaScript: function() return x;
    - C/C++/C#/Java: retorno nome()
    - Delphi: function x():ret
    - Python, etc
  - Procedure não retorna
    - JavaScript: function() return;
    - C/C++/C#/Java: void nome()
    - Delphi: procedure x()
    - Python, etc
  - O que é retorno?
  - Parâmetros
    - Parâmetros dinâmicos
      - JavaScript: arguments
      - C/C++: stdarg.h
      - C#: method(params object[])
      - Java: method(object... myParams)
  - A pilha
    - Como ficam os parâmetros na pilha
    - Como fica o retorno na pilha
    - A diâmica da pilha
      - 1. Empilhar parâmetros, e ponto atual
      - 2. Chamar o método
      - 3. Desempilhar parâmetros para uso
      - 4. Executar
      - 5. Empilhar resultado
      - 6. Saltar para ponto anterior
  - EXIT_CODE
    - Programas são métodos no sistema operacional (main()?)
    - Porque programas precisam retornar um código?
    - O ZERO é ausência de erros, qualquer outro é um código de erro
    - A importância do ExitCode para os scripts de automação
      - https://gist.github.com/erlimar/8fa6e675950b51d19538
    - A importância do ExitCode para a interoperabilidade entre programas, system exec
  - Programa
    - Um programa de computador independente se é orientado a objeto, imperativo ou funcional,
      é a execução de um método (ou função ou procedimento)
    - Uma função ou procedimento é a definição de um programa
    - Programa é: {entrada} -> (execução) -> {saída}
      - A lógica de qualquer programa é:
        - Dada uma mesma entrada, um programa deve retornar sempre o mesmo resultado
        - Um programa é (deve ser) previsível
* Capítulo 5 - Standard library (Biblioteca padrão)
  - libc 
  - rtl no pascal e a biblioteca de componentes
  - dotnet core, coreclr e corefx
  - talvez o termo pilhas embutidas fique melhor aqui
* Capítulo 6 - Compartilhamento, modularização e reutilização
  - Do Ctrl+C Ctrl+V, e-mails a módulos e pacotes
  - using, import, #include, require require_once
  - package managements e os repositórios de pacotes
  - versões e versionamento
    - SemVer
* Capítulo 7 - De cliente/servidor para Web e o "Multiplataforma"
  - Explicar porque não existe a "programação web" e "programação desktop"
  - A rede, o TCP/IP, o Socket e o HTTP
  - Multiplataforma: Linux, macOS, Windows
  - Programas multiplataforma e as diretivas de compilador
    - C/C++/C# #if DEBUG - #ifdef
    - C# Environment
    - Delphi/Pascal {$DEFINE} {$IFDEF}
    - Python import os, NodeJs require('os')
    - Java System.getProperty + java -D{prop.name}={prop.value}
* Capítulo 8 - Tooling (ferramental)
  - aqui é passar a ideia de que ferramentas são necessárias para desenvolver em uma linguagem/plataforma 
  - o quão fácil ou difícil é montar o ambiente
  - compilador, bibliotecas, gerenciador de pacotes, scaffold
  - ex: dotnet, Python + pip, NodeJS + npm
  - no caso de Python, nodejs e Perl, o termo pilhas embutidas 
* Capítulo 9 - Interoperabilidade
  - só falar que não estamos falando de COM/COM+ nem de WebService+SOAP
  - criar extensões PHP, Python, NodeJs
  - Embedded V8, Lua, dotnet, Python 
  - aqui destacamos o poder de C e C++
  - C# DllImport, Java JNI, Wrappers
* Capítulo 10 - Um capítulo que não existe
  - Basicamente explicar porque não falo sobre "banco de dados",
    prevendo que muitos esperariam se falar sobre banco de dados, visto que é algo tão comum
  - Por isso não incluí SQL na lista de linguagens de programação
    - Na verdade SQL é de consulta, assim como HTML é de marcação e CSS é de propriedades de estilo
    - Se fosse incluir SQL em lista de linguagens de programação deveria ser:
      - T-SQL do Microsoft SQL Server
      - PL/SQL do Oracle
      - PL/pgSQL do Postgres
  - Porque não falo de banco de dados?
    - Porque um banco de dados é um recurso (como um arquivo, e de fato é)
    - Porque um SGBD é um programa como outro qualquer
      - que interopera via rede
        - que usa um protocolo próprio com linguagem específica pa operações (SQL)
          - tipo o HTML na Web
      - que interopera por bibliotecas, e tem wrappers para outras linguagens
      - que tem um ferramental (tooling)
* Capítulo 10 - Resumão
  - Explicar o que intendo importante um programador entender
  - Resumir em um parágrafo cada capítulo
  - No resumo do capítulo sobre porque não falo sobre banco:
    - Aqui é um material para programadores de todo e qualquer tipo de programas
    - Um SGBD é um tipo de programa, criado por programadores, que entendem esses recursos
      - você também pode criar um, e não só usar um
      - você não usa um banco, você usa uma biblioteca que serve para armazenamento de dados
      - você não usa um servidor de banco, você se comunica com um programa na rede que serve para armazenamento de dados
* Conclusão
  - Concluir basicamente que um programador de computadores deve saber como as linauguagens funcionam,
    que tipos de linguagens existem, o que é melhor pra cada aplicação, e por fim se especializar
    em determinada área, porém sabendo que sempre pode tirar o melhor proveito do computador se souber
    como ele funciona.
* Bibliografia
