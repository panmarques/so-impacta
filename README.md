# so-impacta

1.	Quais são as diferenças essenciais entre um aplicativo comum (por exemplo, o Microsoft Word) e um sistema operacional?
 R: É a parte do software que fica entre o Hardware e os Programas Aplicativos o Word depende do Sistema Operacional para funcionar, 
 O Sistema Operacional controla e coordena o uso do hardware pelos diversos programas aplicativos de diversos usuários.
2.	Por que um sistema operacional é necessário? R: Porque sem o Sistema Operacional não existe comunicação entre o Hardware e os 
Softwares de aplicações.
3.	Que nome é dado às chamadas realizadas pelas aplicações aos serviços disponibilizados pelo sistema operacional? Mencione como
    exemplo duas destas chamadas. 
R: Exit() e exit()
4.	O que é um processo? R: Processo é um "trabalho " em execução em um sistema computacional.
5.	Um processador com um único núcleo executa vários processos simultaneamente? Explique sua resposta.
R: Não, ele executa um processo por vez porem devido a velocidade ele aparenta fazer múltiplo processamento.
6.	O que ocorre quando o sistema operacional faz o chaveamento entre processos? R: Ao chavear entre processos, o sistema operacional 
salva todo o estado do processo que está em execução e carrega o estado do processo que entrará em execução.
7.	Qual é a diferença entre thread e processo? R: Thread é como é chamada uma execução de uma sequência de instruções e Processo é
um "trabalho " em execução em um sistema computacional. A Diferença é que o processo pode usar várias Thread’s para executar uma tarefa.
8.	Qual é a diferença entre escalonamento preemptivo e não-preemptivo.
R: Caso preemptivo: Quando o processo que está em execução 
(running) muda para o estado de pronto (ready) (por exemplo, devido a uma interrupção). Quando o processo que está em espera (waiting) 
muda para o estado de pronto (ready) (por exemplo, quando uma operação de E/S se encerra). Caso não preemptivo: Quando o processo que
está em execução (running) muda para o estado de espera (waiting). Quando um processo encerra (terminated).
9.	Cite 2 algoritmos de escalonamento de processos e explique o funcionamento de cada um. R: First-Come, First-Served: Neste algoritmo,
os processos são executados na ordem em que chegam ao escalonador. Pode apresentar diferentes tempos médios de espera de acordo com a
ordem de chegada dos processos. Shortest JobFirst: Minimiza o tempo de espera para um conjunto de processos. Associa a cada processo o 
seu próximo tempo de CPU, e prioriza o processo na fila de pronto com o menor tempo.
10.	Cite 2 recursos disponibilizados pelo sistema operacional para ajudar o programador a implementar programas concorrentes 
 sem interferência entre threads, e diga em qual situação é mais conveniente utilizar cada recurso.
R: Semáforo: Mecanismos que garantem que somente N processos podem acessar um certo recurso em um dado momento. 
Passagem de mensagens: Combinação de transferência de dados com exclusão mútua e sincronização.

