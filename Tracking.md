#Introdução
Essa página sintetiza o acompanhamento realizado do projeto SAS durante a release 2.

##Retrospectiva Apresentação Release 1
Na release 1, os alunos de MDS tiveram muita dificuldade em aprender a linguagem nova (Python com Django), e por isso o sistema foi entregue com os casos de uso priorizados incompletos. Incompletos em termo de validações e testes.

Outro ponto levantado na apresentação foram as métricas escolhidas, por não terem ligações entre si.

##Sprint 0
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 0](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-0).
* Como os casos de uso entregues estavam incompletos, e era preciso alinhar conhecimento da linguagem nova e em relação a testes, a primeira sprint foi definida com Technical Stories de teste e validações.
Após a escolha ter sido feita, foi identificado que TS não agrega valor ao cliente, portanto nossa sprint 0 não agregou valor para o cliente.
* Por outro lado a equipe conseguiu alinhar conhecimento de teste entre todos os membros, e também em relação a linguagem.
* Como a equipe de MDS teve dificuldade com a linguagem na release 1, os pareamentos foram definidos com um aluno de MDS e um de GPP. O que acabou impedindo os alunos de MDS a produzirem todos os dias, pois os alunos de GPP fazem estágio e não têm muito tempo disponível.
* Essa sprint foi contabilizada no evm.
* Durante a sprint 0, a equipe estudou e procurou outras métricas para agregar a de complexidade ciclomática e devido a dificuldade não encontrou. Por isso só foram coletados dados de qualidade em relação a cobertura de teste. 

Na tabela abaixo é possível identificar as estórias planejadas (TS e/ou US), bem como seus pontos, se foi concluída ou não. Ao final dela é possível ver o total de pontos planejados, total de pontos concluídos e pendentes.

|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|TS#1|3|X||
|TS#2|5|X||
|TS#3|3|X||
|TS#4|3|X||
|TS#5|3|X||
|TS#6|2|X||
|TS#8|2|X||
|TS#9|3|X||
|TS#10|8||X|
|TS#12|8||X|
|Total Pontos|**40**|24|16|

* O velocity da equipe foi de **24** pontos.

##Sprint 1
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 1](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-1).
* Como citado anteriormente, um problema identificado foi a baixa produtividade de MDS devido ao pareamento, portanto os pareamentos foi designados em sua maioria para duplas entre MDS, e deixando bem claro que todos podem parear com todos.
* Na sprint 1 a cliente (Profa. Carla) priorizou a US mais complexa, o que acabou acarretando na sua não conclusão.
* Para dividir melhor a US#5 priorizada pela cliente, foram criadas tarefas para a mesma.
* A US#5 foi repontuada de 13 pontos para 20, na reunião de planejamento da sprint.
* Nessa sprint foi priorizado o débito técnico TS#12 da sprint anterior.
* Ao final da sprint nenhuma estória foi concluída, porém a equipe trabalhou durante toda a semana. O time identificou que seria melhor fazer o velocity, burndown e evm em relação a _Taks_ (Tarefas) concluídas. O que começou a ser aplicado na sprint seguinte.

Na tabela abaixo é possível identificar as estórias planejadas (TS e/ou US), bem como seus pontos, se foi concluída ou não. Ao final dela é possível ver o total de pontos planejados, total de pontos concluídos e pendentes. Os débitos técnicos também estão presentes na tabela, e para diferenciar estão em itálico.


|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|US#2|8||X|
|US#4|8||X|
|US#5|20||X|
|_TS#12_|_8_||X|
|Total Pontos|**36**|0|36|

* O velocity da equipe foi de **12** pontos.

## Sprint 2
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 2](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-2).
* Nessa sprint foi priorizada a US#3 solicitada pela cliente e as TS#11, TS#13, além dos débitos US#2, US#4, US#5, TS#12 da sprint passada.
* As TS#11 e TS#13 foram repontuadas de 5 para 1, tendo em vista que foram feitas juntamente com outras estórias.
* Nessa sprint o velocity, evm e burndown foram feitos contando tasks concluídas.
* Nessa sprint foi definida a métrica de duplicação de código para agregar com a de complexidade ciclomática.

Na tabela abaixo é possível identificar as estórias planejadas (TS e/ou US), bem como seus pontos, se foi concluída ou não. Ao final dela é possível ver o total de pontos planejados, total de pontos concluídos e pendentes. Os débitos técnicos também estão presentes na tabela, e para diferenciar estão em itálico.

|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|US#3|5|X||
|TS#11|1|X||
|TS#13|1|X||
|_US#2_|8|X||
|_US#4_|8|X||
|_US#5_|_20_|X||
|_TS#12_|_8_|X||
|Total Pontos|**51**|51|0|

* O velocity da equipe foi de **25** pontos.

## Sprint 3
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 3](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-3).
* A estórias foram priorizadas pela equipe, já que nao foi possível contactar a cliente.
* As US#1 e US#6 foram repontuadas de 13 para 8 pontos cada.
* Foram criadas 3 TS (TS#14, TS#15, TS#16).
* As US foram realizadas com TDD.
* Foram criadas TS para melhorar a qualidade.

Na tabela abaixo é possível identificar as estórias planejadas (TS e/ou US), bem como seus pontos, se foi concluída ou não. Ao final dela é possível ver o total de pontos planejados, total de pontos concluídos e pendentes.

|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|US#1 task1|4|X||
|US#1 task2|4|X||
|US#6 task1|4|X||
|US#6 task2|4|X||
|TS#7|2|X||
|TS#14|1|X||
|TS#15 task1|4|X||
|TS#15 task2|3|X||
|TS#15 task3|3||X|
|TS#15 task4|3|X||
|TS#16 task1|1|X||
|TS#16 task2|1|X||
|TS#16 task3|2|X||
|TS#16 task4|4||X|
|Total Pontos|**40**|33|7|

* O velocity da equipe foi de **27** pontos.

##Sprint 4
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 4](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-4).
* Não possível encontrar a Carla, portanto a equipe priorizou as estórias.
* Como dito anteriormente, todo o tracking está sendo feito a partir de tasks, então as tasks pendentes da sprint passada foram priorizadas nessa.

Na tabela abaixo é possível identificar as estórias planejadas (TS e/ou US), bem como seus pontos, se foi concluída ou não. Ao final dela é possível ver o total de pontos planejados, total de pontos concluídos e pendentes. Os débitos técnicos também estão presentes na tabela, e para diferenciar estão em itálico.

|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|US#7 task1|6|X||
|US#7 task2|2|X||
|US#10 task1|2|X||
|US#10 task2|1|X||
|US#10 task3|1|X||
|US#10 task4|3|X||
|US#10 task5|1|X||
|US#11 task1|3|X||
|US#11 task2|3|X||
|US#11 task3|2|X||
|US#11 task4|5|X||
|TS#17|2|X||
|_TS#10_|_5_|X||
|_TS#15 task3_|_3_|X||
|_TS#16 task4_|_4_||X|
|Total Pontos|**43**|39|4|

* O velocity da equipe foi de **29,4** pontos.

##Sprint 5
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 5](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-5).
* O sistema foi apresentado para a cliente, onde a mesma criou várias estórias que estão priorizadas nessa sprint.

Na tabela abaixo é possível identificar as estórias planejadas (TS e/ou US), bem como seus pontos, se foi concluída ou não. Ao final dela é possível ver o total de pontos planejados, total de pontos concluídos e pendentes. Os débitos técnicos também estão presentes na tabela, e para diferenciar estão em itálico.

|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|US#8|1|X||
|US#12|3|X||
|US#13|2||X|
|US#14|5||X|
|US#15|3|X||
|US#16|5|X||
|US#17|3|X||
|TS#18|5|X||
|TS#19|2|X||
|TS#20|5||X|
|_TS#16 task4_|_4_||X|
|Total Pontos|**38**|22|16|

* O velocity da equipe foi de **28,2** pontos.

##Sprint 6
* Mais informações sobre a sprint, podem ser encontradas em [Sprint 6](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-6).
* A cliente solicitou a inclusão de tags (#) durante a criação da reserva, para no futuro serem gerados relatórios de acordo com essas tags. Por isso essa nova US foi priorizada para a sprint.
* A cliente achou mais importante priorizar essa nova US do que a de criar relatório, por isso a US de criar relatório não será feita até o momento.
* Os débitos da sprint passada também foram priorizados.
* Portanto a US#9 e a TS#20 foram as estórias pendentes para o projeto SAS.

|Estória Planejadas|Pontos da Estória|Estória Concluída|Estória Pendente|
|------------------|-----------------|-----------------|----------------|
|US#18|20|X||
|_US#13_|_2_|X||
|_US#14_|_5_|X||
|_TS#20_|_5_||X|
|_TS#16 task4_|_4_|X||
|Total Pontos|**36**|31|5|

* O velocity da equipe foi de **28,6** pontos.

###Velocity
O velocity da equipe pode ser visto na figura abaixo, vale ressaltar que os pontos planejados das tabelas acima somam também os débitos, já na figura de velocity abaixo os débitos não foram somados tendo em vista que esses pontos já foram planejados em outra sprint.

![Velocity total](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_velocityTab.png)

###Burndown da Release 2

A imagem abaixo ilustra o burndown da Release 2. A linha em azul, descreve como seria a queima de pontos, caso estes fossem divididos de forma uniforme durante toda a Release. Foram calculados a divisão de 148 em 49 dias, o que implicaria na queima diária de aproximadamente 3 pontos. Porém, a produtividade do time não foi contínua e além disso houveram que foram repontuadas, para mais ou para menos, e novas estórias criadas, com o decorrer das sprints. Dessa forma, observa-se na curva em vermelho a produção real do time. Ressalta-se também que ao final da Release 2 houve o débito de 25 pontos, das estórias: TS #20 e US #9.

![Velocity total](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/release_burndown.png)
