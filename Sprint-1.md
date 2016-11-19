# 1. Planejamento da Sprint
O foco desta sprint reside na implementação de histórias de usuários voltadas ao usuário Administrador. Todas as histórias foram priorizadas pela cliente Carla Rocha. 

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Pedro       | Allan      |<ul><li>Elaine</li><li>Fabiola</li><li>Gustavo</li><li>Hugo</li><li>Jessica</li><li>Lucas</li><li>Luís</li><li>Vitor</li>  |

## 1.2. Backlog

| US (User Story) | História | Pontuação | Nova Pontuação| Responsável |
|----------------------|----------|---------|------------|-------------|
| #2 | Como um administrador, quero consultar todas reservas já efetuadas visualizando todos dados. | 8  |---| Vitor |
| #4 | Como administrador, quero excluir qualquer reserva efetuada. | 8  |---| Gustavo |
| #5 | Como um usuário, quero consultar a disponibilidade e as reservas já realizadas em determinado espaço. |13| 20  | Lucas e Luis, Hugo e Fabíola, Vitor e Hugo, Pedro e Lucas, Fabíola e Elaine, Luis e Hugo |
|**Total**| | **24**|||

#### Tarefas da História #5
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Criar template das tabelas de reservas. | 1  | Allan |
| Criar a tabela de período por sala. | 4 | Lucas e Luis |
| Criar a tabela de semana por sala. | 4  | Hugo e Fabíola |
| Criar a tabela de prédio por dia. | 4 | Vitor e Hugo |
| Criar a tabela de semana por reserva. | 4  | Pedro e Lucas |
| Criar formulário de filtros para pesquisa. | 2 | Fabíola e Elaine |
| Integrar todas as tabelas. | 1 | Luis e Hugo |

###Débitos técnicos
| TS (Technical Story) | História | Pontuação | Responsável |
|----------------------|----------|-----------|-------------|
| #12 | Como um desenvolvedor, eu quero refatorar o cadastro de criação de reserva para consertar os bugs conhecidos. | 8  | Allan e Lucas |

## 1.3. Quadro de Conhecimentos
o seguinte quadro de conhecimento, demonstra um pequeno avanço com relação a Sprint 0. 
![Quadro de Conhecimentos](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/1_conhecimento.png) 

## 1.4. Quadro de pareamento
Os pareamentos dessa Sprint não foram pre-definidos como na Sprint 0, decisão comada a partir da retrospectiva da sprint anterior, onde ficou claro que os pareamentos pre-definidos dificultou a interação da equipe por conta dos horários. O quadro de pareamento a seguir demonstra o monitoramento dos pareamentos.
 
![Quadro de Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/1_pareamento.png) 

## 1.5. Restrospectiva
| Pontos Positivos |
|------------------|
| Pareamento bastante produtivo, onde pôde-se aprender bastante |
| Maior independência de MDS em relação a GPP |

|Pontos Negativos |Causa| Melhoria|
|-----------------|-----|---------|
|Poucas reuniões diárias na semana| Outras disciplinas| Tentar organizar melhor os horários|
|Desenvolvimento deixado para última hora| Como não havia um par responsável, ninguém se cobrou| Designar um par para cada história|
|Quadros (pareamento, conhecimento e kanban) não atualizados durante a Sprint | Codificação constante|GPP não se dedicar completamente ao código|
|Pareamento falho|Outras disciplinas| Designar um par para cada história|
|Nenhum ponto entregue| Nenhuma história foi finalizada por completo| Dividir as histórias em tarefas e pontuá-las|
|Diminuição da integração do time| Os alunos de MDS ficaram responsáveis pelas histórias e em procurar os alunos de GPP para parear, mas isso não ocorreu| Já definir um par para a história, podendo a mesma ser feita com um dos responsáveis e outro par|

# 2. Resultados:

## 2.1. Burndown
Durante a sprint 1, o time não conseguiu finalizar nenhuma história planejada nem a dívida técnica priorizada. Assim, um débito de 36 pontos foi registrado, devido ao mau planejamento e distribuição das tarefas da sprint, além da existência de outros compromissos igualmente importantes como provas de disciplinas, dificuldade da história e pareamentos desoranizados.

![Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/1_burndown.png) 

## 2.2 Velocity
O velocity desta sprint foi de **12 pontos**. Esta pontuação refere-se a média de pontos concluídos entre a Sprint 0 e esta sprint. A diminuição considerável ocorreu em virtude da não conclusão de pontos na atual Sprint.

![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/1_velocity.png)

## 2.3 Agile EVM

![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/1_evm.png)

**OBS.** As descrições e fórmulas das siglas apresentadas na tabela acima estão devidamente explicitadas [aqui](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Agile-EVM). Neste mesmo link pode ser encontrada a tabela de EVM completa do projeto.

Foram planejado 24 pontos para essa Sprint, e entregues 0. O RPC (Pontos Completos Na Release) ficou então 24, o APC (Porcentagem Completa Real) ficou em 16,22% abaixo do PPC (Porcentagem Planejada Completa) de 25,00%, o que indica atraso no projeto e necessidade de gerenciar esse risco. Não foi adicionado nenhum ponto novo ao projeto, PA (Pontos Adicionados) = 0.

## 2.4. Qualidade
### 2.4.1 Integração Contínua
A integração contínua do projeto permanece passando e estável, pois com a não conclusão das histórias, nada foi incluído em ambas as ramificações.

![Travis CI](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint0/travis.png) 

### 2.4.2 Cobertura de Teste
A cobertura de teste permanece a mesma, pois com a não conclusão das histórias, nada foi incluído nas branchs analisadas (dev e master).

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint0/coveralls.png)