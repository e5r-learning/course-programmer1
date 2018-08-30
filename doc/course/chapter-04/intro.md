Capítulo 4 - Funções, procedimentos, parâmetros e retorno
=========================================================

Naveguação | [ANTERIOR][_A] | [TOPO][_H] | [PRÓXIMO][_P]
-----------|----------------|------------|--------------

> TODO: ...

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

Naveguação | [ANTERIOR][_A] | [TOPO][_H] | [PRÓXIMO][_P]
-----------|----------------|------------|--------------

<!-- Links de navegação -->
[_A]: ../chapter-03/intro.md "Capítulo 3 - A dinâmica e estrutura de um programa"
[_H]: ../index.md "Topo"
[_P]: ./x.md "x..."

<!-- Outros links -->
