# Respostas

1.
O Docker Swarm permite a orquestração de containers em um cluster distribuído, utilizando nós do tipo manager e worker para dividir tarefas e garantir escalabilidade e alta disponibilidade. Já o Docker Compose é voltado para a definição e execução de múltiplos containers em um único host, sendo mais utilizado em ambientes de desenvolvimento.

2.
Em um cluster Docker Swarm, os nós do tipo Manager são responsáveis por gerenciar o cluster, distribuindo tarefas, mantendo o estado desejado e monitorando os serviços. Já os nós Worker executam as tarefas atribuídas, rodando os containers e reportando seu status aos managers.

3.
A) docker swarm init
B) O driver de rede padrão é o overlay, que permite a comunicação entre serviços distribuídos em diferentes nós do cluster.




