DEADLOCK (acontece tanto em sistemas operacionais quanto em banco de dados)

Deadlock (interbloqueio, blocagem, impasse), no contexto de sistemas operacionais (SO), refere-se a uma situação em que ocorre um impasse, e dois ou mais processos ficam impedidos de continuar suas execuções - ou seja, ficam bloqueados, esperando uns pelos outros.

Tanenbaum: 
 - Um conjunto de processos estará em situação de deadlock se todo processo pertencente ao conjunto estiver esperando por um evento que somente um outro processo desse mesmo conjunto poderá fazer acontecer.



Em muitos casos, um processo não necessita apenas de acesso exclusivo a somente um recurso, mas sim a vários. Por exemplo, dois processos querem gravar em CD um documento obtido pelo scanner. O processo A está usando o scanner, enquanto o processo B, que é programado diferentemente, está usando o gravador de CD. Então, o processo A pede para usar o gravador de CD, mas a solicitação é negada até que o processo B o libere. Porém, ao invés de liberar o gravador de CD, o processo B pede para usar o scanner. Nesse momento, ambos os processos ficam bloqueados e assim ficarão para sempre. Essa situação é denominada deadlock.


O deadlock pode ocorrer mesmo que haja somente um processo no SO, considerando que este processo utilize múltiplos threads e que tais threads requisitem os recursos alocados a outros threads no mesmo processo;

O deadlock independe da quantidade de recursos disponíveis no sistema;



FONTES: 
- https://pt.wikipedia.org/wiki/Deadlock
- https://www.devmedia.com.br/introducao-ao-deadlock/24794