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
| #14 | Como um desenvolvedor, eu quero internacionalizar o SAS para inglês. | --- |1|Elaine|
| #15 |Como um desenvolvedor, eu quero refatorar as views, para melhorar a qualidade do código. |---| 13|Gustavo e Allan|
| #16 |Como desenvolvedor, eu quero refatorar a criação de reservas, para ficar mais intuitivo. |---|8|Gustavo e Jessica|

As histórias US#1, US#6 e TS#15 foram divididas em tarefas e cada uma delas foi devidamente pontuada.

#### Tarefas da História #1
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Criar estrutura de administrador no sistema | 4 | Hugo e Fabíola |
| Criar backend de consulta | 4 | Hugo e Fabíola |

#### Tarefas da História #6
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Criar backend para transformar um usuário em admin | 4 | Vitor, Luis e Lucas |
| Integrar com frontend| 4 | Vitor, Luis e Lucas |

#### Tarefas da História Técnica #15
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
|Diminuir complexidade da user view| 4 | Gustavo e Allan |
|Diminuir complexidade da booking view| 3 | Gustavo e Allan |
|Diminuir duplicidade de código na user view| 3| Gustavo e Allan|
|Diminuir duplicidade de código booking view| 3| Gustavo e Allan|

## 1.3. Quadro de Conhecimentos

## 1.4. Quadro de pareamento

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
![Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_burndown.pn)

## 2.2 Velocity
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_velocity.pn)

## 2.3 Agile EVM


## 2.4. Qualidade

### 2.4.1 Integração Contínua
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/travis.PN)

### 2.4.2 Cobertura de Testes
A cobertura de testes subiu de 68% na Sprint 1 para 82% na Sprint 2

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/coveralls.PN)

<hr>
<b>** Extrato Code Climate para Duplicação, Complexidade e PEP8 abaixo **</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/code_climate.PN)

<b>** Identificação de Duplicação, Complexidade e PEP8 de acordo com as Issues**</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/metrics.PN)

### 2.4.3 Duplicação de Código


### 2.4.4 Complexidade Ciclomática

### 2.4.5 Estilo: PEP8

### 2.4.6 Ações definidas para melhoria da qualidade