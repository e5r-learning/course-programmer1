Os programas de computador
==========================

Naveguação | [ANTERIOR][_A] | [INÍCIO][_H] | [PRÓXIMO][_P]
-----------|----------------|------------|--------------

> Um programador é uma pessoa que programa um computador para executar uma tarefa específica.

O trabalho de um computador, como vimos no capítulo anterior, é basicamente calcular um punhado de dados que foram fornecidos previamente e após chegar ao resultado final, aprentá-lo.

Mas como ele faz esse cálculo é realmente a parte importante.

O cálculo é uma execução finita de operações que ocorrem em uma ordem específica, partindo da primeira até chegar a última, que é quando o resultado é obtido, e por fim apresentado a nós.

> No capítulo anterior, onde falamos sobre o computador, aprendemos que a parte que faz a computação em si é o [microprocessador][MICROPROCESSADOR-LINK], esse é o computador em si.

Basicamente em cada computador ([microprocessador][MICROPROCESSADOR-LINK]) nós temos uma sequência de informações que são registradas (gravadas) sequencialmente, e cada uma dessas informações (chamadas instruções) direcionam a corrente elétrica por um caminho específico. Então quando nós alimentamos o computador com energia ele começa na primeira instrução e vai fluindo até chegar na última.

O que o computador está fazendo quando percorre este caminho, não é nada mais nada menos do que seguir um roteiro pré-estabelecido. Esse roteiro é um programa. Ou seja, o computador recebe um programa (roteiro) pra seguir, e simplesmente faz isso.

Essas instruções dizem basicamente pra o computador ligar/desligar uma chave, que por sua vez pode acender uma luz de LED ou emitir um som ou outra coisa do tipo. Outras instruções podem dizer pra o computador voltar para o início, ou ir pra outro ponto do fluxo (é o que chamamos de salto); e várias outras instruções. E o computador fará isso enquanto houver energia e até que chegue ao final do seu programa e dê seu trabalho como encerrado.

Então, um programa de computador é uma sequência de instruções que ele (o computador) obedece segamente.

## Me permita uma ilustração a mais

Sei que não ajudou muito ainda, porque imagino que algumas coisas permanecem obscuras. Mas ainda me deixe por um pouco de tempo nesse mundo abstrato, pois quero lhe dar mais um exemplo.

Hoje um computador faz coisas incríveis, que como já mencionamos, parecem mágicas. Um jogo 3D onde o personagem parece uma pessoa real, ou fazer uma pergunta a um smartphone e ouví-lo respondendo com uma voz que imita uma pessoa perfeitamente, isso tudo nos faz aceitar que essa é uma ciência muito complexa (e realmente o é), mas a complexidade está muito na aplicação, velocidade e quantidade dessas instruções, além é claro nos dispositivos que são usados para que possamos observar os resultados. Mas o princípio é o mesmo, e ele é bem básico.

O computador, nos primórdios, antes de ser uma máquina totalmente digital; era uma mistura de partes elétricas e mecânicas. Depois todas as partes mecânicas foram substituídas por partes digitais, mas essas partes digitais fazem o mesmo trabalho que as partes mecânicas faziam antes, a vantagem é que são bem menores, minúsculas, na verdade quase invisíveis.

Imagine uma faixada inteira de um prédio de 20 andares coberta por lâmpadas enfileiradas uma ao lado da outra até cobrir toda a faixada do prédio. E essas lâmpadas conectadas cada uma a um fio gigante com um plug na ponta que acabava em uma mesa. Na mesa você tinha exatamente a mesma quantidade de tomadas para cada plug das lâmpadas, no formato e posição da faixada do prédio. Se você conectar o plug correspondente de uma lâmpada da faixada na mesa ela irá acender.

Então você chega nessa mesa com os plugs na mão, liga alguns interruptores e deixa outros desligados. Você foi percorrendo os plugs de cada lâmpada um a um na mesa e decidindo: esse eu ligo, e esse eu não ligo. Até chegar ao último.

Ao final digamos que sua mesa ficou como no desenho abaixo. Vamos imaginar que ligado é um `#` (cerquilha) e desligado é um `.` (ponto). Então você deixou sua mesa assim:

```
................
................
................
.####......####.
#######..#######
################
.##############.
..############..
...##########..
.....######.....
.......##.......
................
................
```

Então alguém que está do lado de fora bem distante do prédio olha e vê o desenho de um coração gigante.

Agora junte a isso o fato de você conseguir entender que `#` é ligado e `.` é desligado. Então se eu escrever em um papel um desenho diferente e der pra você dizendo, faz de novo só que agora seguindo esse roteiro no papel. Nós poderíamos criar vários desenhos pras pessoas olharem de fora.

No final, as lâmpadas na faixada são o dispositivo de saída, você é o processador (aquele que processa a informação), no papel as instruções que você consegue entender (o programa), e eu que escrevi no papel seria o programador.

O que um processador faz é exatamente isso, só que em escala de tamanho infinitamente menor e em escala de velocidade infinitamente maior.

Sei que parece inútil esse exemplo, mas quando hoje você envia um simples "smile" pelo [WhatsApp][WHATSAPP-LINK], e a pessoa o vê no outro aparelho. O que ela vê é o mesmo que essa pessoa do exemplo (que está do lado de fora do prédio) também vê. Só que ao invés da faixada do prédio é a tela do smartphone dela, que é bem menor e bem mais colorida.

Aqui nós compreendemos que com os componentes digitais podemos reduzir incrivelmente o tamanho das peças mecânicas que usávamos antes, e com isso podemos fazer coisas muito mais incríveis. Mas uma coisa você precisa compreender, o princípio básico é bem simples: Um processador segue um programa com instruções conhecidas e obedece.

## Mais uma ilustração

[Neste link][VIDEO1-LINK] temos um vídeo com o funcionamento de uma calculadora antiga chamada __BUSICOM HL-21__, caso o vídeo não esteja mais disponível no momento que você lê este material, procure por vídeos na Internet sobre este assunto que acredito existir muito material disponível.

No vídeo em questão você vê uma máquina mecânica com números e pequenas alavancas que podem ser posicionadas e acionadas.

O que ela faz é bem simples, você usa os cilindros pra posicionar números, e aciona as alavancas para marcá-los. De modo que você informa um primeiro número depois um segundo número e então quando tudo está posicionado, você aciona uma outra alavanca que inicia a execução de um programa pré-estabelecido no equipamento, que vai acionando as alavancas e girando os cilindros, até chegar ao final. O objetivo do programa é fazer a divisão do primeiro número pelo segundo. Quando chega ao final, tudo pára e o número com resultado final da operação está lá pra você ver.
No vídeo o cálculo feito é "123456789" dividido por "1234" que resulta precisamente em "100046".

É uma calculadora primitiva, ou seja, um computador com um programa pré-estabelecido para calcular números e exibir os resultados. Da mesma forma como o exemplo das lâmpadas na faixada do prédio, só que agora com outro propósito. Mas o princípio continua o mesmo.

## Uma última ilustração

É claro que os computadores que nos referimos aqui nesse pequeno curso não são esses. São computadores capazes de fazer infinitamente mais coisas. Inclusive não se tratam de máquinas mecânicas ou eletromecânicas, mas sim de máquinas digitais.

Mas à final o que é uma máquina digital?

Antes disso quero apresentar um outro nome que o computador recebe. Nós falamos antes do [microprocessador][MICROPROCESSADOR-LINK], que é basicamente o computador. Mas nós também temos o [microcontrolador][MICROCONTROLADOR-LINK] que é quase a mesma coisa.

Enquanto nos referimos ao [microprocessador][MICROPROCESSADOR-LINK] como o computador que deve ser ligado a dispositivos de entrada e saída pra fazer o que precisamos, também podemos nos referir ao computador como [microcontrolador][MICROCONTROLADOR-LINK].

Porém o microcontrolador já vem com tudo conectado a ele, com a memória e os dispositivos de entrada e saída, só que esse por sua vez é bem menos potente e simples do que [microprocessador][MICROPROCESSADOR-LINK]. E isso porque ele é usado somente para controlar algumas coisas mais específicas, daí o nome [microcontrolador][MICROCONTROLADOR-LINK]. Mas em linhas gerais se tratam da mesma coisa, um computador.

[Neste link][VIDEO1-LINK] temos um vídeo bem legal da construção de um gravador de [PIC][PIC-LINK]. Aqui eles estão construíndo um dispositivo que vai ser usado pra gravar um determinado programa em um [microcontrolador][MICROCONTROLADOR-LINK].

A parte da criação do gravador e toda a parte química aqui envolvida não nos interessa. Eles vão falar de diodo, solda, e etc. Mas chegando lá pra o minuto 8:05 eles mostram um programa escrito com instruções do [microcontrolador][MICROCONTROLADOR-LINK] para o qual eles estão trabalhando, e usando um programa eles irão compilar ([veremos isso mais a frente][COMPILAR-LINK]) e por fim usar o dispositivo que eles criaram pra gravar na memória do [microcontrolador][MICROCONTROLADOR-LINK].

O [microcontrolador][MICROCONTROLADOR-LINK] então, já está com o programa gravado em sua memória, e tem suas saídas todas já definidas. Eles irão conectar essas saídas em uma placa, ligando alguns pontos a um LED.

A partir do momento que o [microcontrolador][MICROCONTROLADOR-LINK] for ligado na energia ele começa a executar as instruções que foram estabelecidas (escritas) no programa que está na sua memória até chegar ao final, ou quando a energia acabar. No caso do programa em si, você vai perceber que as instruções que ele emite são, liga, espera um tempo, desliga; e depois pula pro começo novamente.

Então esse é um programa que fica ligando e desligando uma saída de energia, e como essa saída está ligada em uma lâmpada LED, podemos dizer que é um programa que faz piscar um LED eternamente.

Você conseguirá ver essa demonstração do funcionamento da execução do programa pelo [microcontrolador][MICROCONTROLADOR-LINK] lá pelo minuto 11:30 do [vídeo][VIDEO1-LINK].

## Chega de ilustrações, vamos concluir

Ainda existem outras coisas que podemos falar, e de fato já demos algumas pitadas nesse texto, coisas como memória e gravação delas, coisas como o próprio texto dos programas que você pode ver um pouco nos vídeos, aí já entra o fato da própria linguagem da programação ([vamos ver isso em outro tópico][LINGUAGEM-LINK]), e uma série de outras coisas. Mas iremos tratar de cada item no momento certo.

Aqui o que importa é você saber que os programas de computador são as instruções que gravamos no processador para ele seguir como roteiro e fazer o que nós queremos, apresentando o resultado no formato adequado de acordo com os dispositivos que nos for melhor.

Passamos por ilustrações bem antigas, mas a simplicidade delas nos permitem entender o funcionamento exato da execução de um programa de computador.

Os exemplos que usamos foram de [microcontrolador][MICROCONTROLADOR-LINK] e que são [microprocessador][MICROPROCESSADOR-LINK] bem simples, e se conectam a dispositivos de saída bem primários (como LED's). E os computadores como usamos hoje são chamados de computadores de propósito geral, pois podemos usá-los para vários propósitos na mesma máquina.

Hoje em dia um computador como o que você provavelmente está usando agora tem tantos dispositivos de entrada/saída que não dá nem pra contar. Mas ele também tem as peças fundamentais para o fazer funcionar, são elas:

* A memória onde nós iremos gravar nossos programas
* O próprio processador (que é o computador) que irá fazer nosso trabalho
* O teclado onde iremos usar para informar nossas instruções
* A tela que será o dispositivo de saída que mais iremos utilizar

Uma última coisa que gostaria de mencionar é que, nos exemplos que apresentamos aqui, basicamente nós tinhamos um único programa que era gravado na memória do computador e esse após ligado executa esse programa eternamente.

Hoje os computadores que usamos nos permite na verdade ficar modificando esse programa durante o momento em que ele já está executando. Em outras palavras, nós ligamos o computador, e ele executa um programa que nos permite, usando os dispositivos de entrada instruí-lo a gravar novos programas em sua memória, e passar a executá-los já imediatamente.

Um outro detalhe que não mencionamos ainda (só implicitamente) é que esses programas são gravados em forma binária e não como um texto como esse que você está lendo agora, [mas isso também iremos tratar em outro tópico quando chegar a hora][BINARIO-LINK].

Mas não se prenda a esses detalhes por enquanto, eles serão elucidados no decorrer do curso. Por agora, você só precisa entender o que é um programa de computador e qual a relação dele com o próprio computador. Ou seja, o programa são as instruções dadas ao computador para executar as ações que nós queremos.

Naveguação | [ANTERIOR][_A] | [INÍCIO][_H] | [PRÓXIMO][_P]
-----------|----------------|------------|--------------

<!-- Links de navegação -->
[_A]: ./computers.md "O mundo dos computadores"
[_H]: ../../../README.md "Início"
[_P]: ./bin.md "O formato binário"

<!-- Outros links -->
[MICROPROCESSADOR-LINK]: https://pt.wikipedia.org/wiki/Microprocessador
[MICROCONTROLADOR-LINK]: https://pt.wikipedia.org/wiki/Microcontrolador
[PIC-LINK]: https://pt.wikipedia.org/wiki/Microcontrolador_PIC
[WHATSAPP-LINK]: https://www.whatsapp.com/?lang=pt_br
[VIDEO1-LINK]: https://www.youtube.com/watch?v=rlkDIZxyTcc
[VIDEO2-LINK]: https://www.youtube.com/watch?v=BLAoA-LGTyk
[LINGUAGEM-LINK]: ../chapter-02/intro.md
[COMPILAR-LINK]: ./compiler.md
[BINARIO-LINK]: ./bin.md