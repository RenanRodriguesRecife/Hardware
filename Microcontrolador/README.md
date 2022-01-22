Principais componentes internos de um microcontrolador


<img src="/.assets/microcontrolador.JPG">

CORE

É o núcleo principal do microcontrolador, responsável por executar as instruções do firmware.
Existem dois tipos principais de arquiteturas deste núcleo interno: RISC e CISC.

RISC: Reduced instruction Set Computer. Arquitetura que implementa um número reduzido de instruções simples, de modo a simplificar o núcleo e funcionar com um clock mais rápido. Exemplos: ARM, AVR.

CISC: Complex Instruction Set Computer. Implementa um grande número de instruções, possuindo diversas instruções especializadas. Exemplos: 8051, 68HC11.

RAM

RAM: Random Access Memory: Armazena os dados temporários da execução do firmware. É um tipo de memória volátil, onde os dados são perdidos quando o microcontrolador é deslidado.

FLASH

FLASH: Memória não volátil, utilizada para armazenar o firmware
do microcontrolador.

OSC

Oscilador: Para o funcionamento do microcontrolador é necessário uma fonte de clock, para ditar o ritmo em que as instruções são executadas.
A maior parte dos microcontroladores possuem osciladores internos e externos.
Os osciladores internos possuem uma precisão limitada, com 1% de tolerância ou mais. Isto limita suas aplicações em relógios, por exemplo.
Ninguém quer um relógio que atrasa 10 minutos por dia.
Já os externos, normalmente a cristal, permitem precisões bem melhores de até algumas parte por milhão.

GPIO

GPIO: General Purpose Input Output.
É a seção responsável pelo controle, acionamento e leitura dos pinos dos microcontroladores.
Os pinos podem operar como entradas ou saídas.
Boa parte dos microcontroladores permitem habilitar resistores internos de pull-up ou pull-down nos pinos. Estes resistores tem valores da ordem de dezenas de kilo ohms.
No modo de saída é possível operar normalmente em dois modos: push-pull ou open dran.

TIMER

Um timer de um microcontrolador permite a medição de tempo, contagem de eventos. Pode ser utilizado como base de tempo para outros periféricos do microcontrolador, como por exemplo disparar a conversões períodicas do conversor analógico-digital.