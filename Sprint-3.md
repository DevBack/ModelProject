# 1. Planejamento da Sprint
Não conseguimos entrar em contato com a Carla, por isso as estórias foram priorizadas pelo time na reunião de planejamento. 

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Gustavo       | Jessica      |<ul><li>Allan</li><li>Elaine</li><li>Fabiola</li><li>Hugo</li><li>Lucas</li><li>Luís</li><li>Pedro</li><li>Vitor</li>  |

## 1.2. Backlog

| US (User Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-----------|-----------|
| #1 | Como um administrador, quero consultar os dados de todos os usuários cadastrados no sistema. | 13 |8| Hugo e Fabíola |
| #6 | Como um administrador, quero gerenciar administradores do sistema de modo que consiga tornar um usuário do corpo acadêmico em administrador. | 13 | 8| Luis, Lucas e Vítor|

| TS (Technical Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-------------|-------------|
| #7 | Como um desenvolvedor, eu quero testar a consulta de usuário para garantir a funcionalidade do método. |3|---|Hugo e Fabíola|
| #14 | Como um desenvolvedor, eu quero internacionalizar o SAS para inglês. | --- |1|Elaine|
| #15 |Como um desenvolvedor, eu quero refatorar as views, para melhorar a qualidade do código. |---| 13|Gustavo e Allan|
| #16 |Como desenvolvedor, eu quero refatorar a criação de reservas, para ficar mais intuitivo. |---|8|Gustavo e Jessica|

As histórias US#1, US#6, TS#15 e TS#16 foram divididas em tarefas e cada uma delas foi devidamente pontuada.

#### Tarefas da História #1
|N| Tarefa | Pontuação | Responsável |
|---|--------|-----------|-------------|
|1| Criar estrutura de administrador no sistema | 4 | Hugo e Fabíola |
|2| Criar backend de consulta | 4 | Hugo e Fabíola |

#### Tarefas da História #6
|N| Tarefa | Pontuação | Responsável |
|---|--------|-----------|-------------|
|1| Criar backend para transformar um usuário em admin | 4 | Vitor, Luis e Lucas |
|2| Integrar com frontend| 4 | Vitor, Luis e Lucas |

#### Tarefas da História Técnica #15
|N| Tarefa | Pontuação | Responsável |
|---|--------|-----------|-------------|
|1|Diminuir complexidade da user view| 4 | Gustavo e Allan |
|2|Diminuir complexidade da booking view| 3 | Gustavo e Allan |
|3|Diminuir duplicidade de código na user view| 3| Gustavo e Allan|
|4|Diminuir duplicidade de código booking view| 3| Gustavo e Allan|

#### Tarefas da História Técnica #16
|N| Tarefa | Pontuação | Responsável |
|---|--------|-----------|-------------|
|1|Replanejar fluxo de atividades| 1 | Jessica |
|2|Remodelar campos| 1 | Gustavo e Jessica |
|3|Adicionar framework res| 2| Gustavo|
|4|Adaptar JavaScript| 4| Gustavo e Elaine|

## 1.3. Quadro de Conhecimentos
![Quadro de Conhecimento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_conhecimento.png)

Os conhecimentos da equipe continuam a evoluir, isso graças a integração do time e ao processo de desenvolvimento. A grande lacuna de conhecimento encontra-se em CSS o que não é critico para o desenvolvimento do produto, tendo em vista o pouco volume de trabalho necessário com essa tecnologia.

## 1.4. Quadro de Pareamento
Segue o quadro de monitoramento dos pareamentos.
![Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_pareamento.png)

Os pareamentos estão sendo feitos entre toda a equipe, mesmo sendo escolhidos de forma livre, o que demonstra uma boa integração do time.

## 1.5. Retrospectiva
|Pontos Positivos|
|----------------|
|Muito aprendizado|
|Maior integração|
|Trabalho contínuo|

|Pontos Negativos |Causa| Melhoria|
|-----------------|-----|---------|
|Qualidade de código|Falta de experiência da equipe|GPP apontou os tópicos e sugeriu melhorias|
|Dificuldade de pareamento presencial|Semana Universitária|Encontrar na FGA|

# 2. Resultados:

## 2.1. Burndown
![Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_burndown.png)

## 2.2 Velocity
O velocity desta sprint foi de **27 pontos**. Alguns pontos ficaram pendentes, mas esse velocity reflete a média dos pontos da sprint 0 até a 3. A tabela utilizada par ao cálculo do velocity e o gráfico podem ser vistos abaixo.

![VelocityTab](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_velocityTab.png)
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_velocity.png)

## 2.3 Agile EVM
![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_evm.png) 

**OBS.** As descrições e fórmulas das siglas apresentadas na tabela acima estão devidamente explicitadas [aqui](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Agile-EVM). Neste mesmo link pode ser encontrada a tabela de EVM completa do projeto.

Foram priorizados 40 pontos para essa Sprint, formam entregues 33. O RPC (Pontos Completos Na Release) ficou em 108, o APC (Porcentagem Completa Real) subiu para 51,02% acima do PPC (Porcentagem Planejada Completa) de 83,08, . Tendo em vista que na Sprint1 o projeto estava atrasado esses dados demonstram uma boa reação da equipe. Não foi adicionado nenhum ponto novo ao projeto, PA (Pontos Adicionados) = 0.
O Backlog do Produto foi replanejado em -8 pontos, PR (Pontos Replanejados) = -8, o que mudou a percepção sobre o volume de produto que foi acordado inicialmente, agora o PRP (Pontos Planejados Da Release) = 147.
## 2.4. Qualidade

### 2.4.1 Integração Contínua
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint3/travis.PNG)

### 2.4.2 Cobertura de Testes
A cobertura de testes subiu de 82% na Sprint 2 para 87% na Sprint 3

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint3/coveralls.PNG)

<hr>
<b>** Extrato Code Climate para Duplicação, Complexidade e PEP8 abaixo **</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint3/code_climate.PNG)

<b>** Identificação de Duplicação, Complexidade e PEP8 de acordo com as Issues**</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint3/metrics.PNG)

### 2.4.3 Duplicação de Código
Das 124 issues (dobro em relação a sprint anterior), 74 são de duplicação de código, a grande maioria irresolvível. A equipe optou por não considerar nenhuma ação nesta sprint quanto a duplicação de código, em razão das refatorações a caminho.

### 2.4.4 Complexidade Ciclomática
7 issues de complexidade ciclomática identificadas, mesma quantidade que na sprint anterior, sendo uma nova acrescentada neste sprint e uma (em booking/views.py) resolvida de acordo com [#65](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/65) 

### 2.4.5 Estilo: PEP8
Das 124 issues identificadas, 43 são de adequação ao PEP8, todas elas em sas/sas/basic.py

### 2.4.6 Ações definidas para melhoria da qualidade
Agir em torno das issues de complexidade ciclomática somente nas views.py (booking e user) devido ao fim da release estar se aproximando e a alta carga de trabalho mais urgente.