# 1. Planejamento da Sprint
O foco desta sprint reside na implementação de histórias de usuários voltadas ao usuário Administrador. Todas as histórias foram priorizadas pela cliente Carla Rocha. 

<b>
Em virtude do tempo de duração de sprint, definido em uma semana, estar se mostrando insuficiente à conclusão de User Stories devido à carga de trabalho demandada, a equipe definiu fazer uma subdivisão dos pontos definidos às User Stories em tarefas de forma a realizar o acompanhamento (Burndown, Velocity, EVM) mais granular, preciso e com menos dependências, sem comprometer a produtividade da equipe já habituada à agilidade semanal de produção.
</b>

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Jessica       | Hugo      |<ul><li>Allan</li><li>Elaine</li><li>Fabiola</li><li>Gustavo</li><li>Lucas</li><li>Luís</li><li>Pedro</li><li>Vitor</li>  |

## 1.2. Backlog

| US (User Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-----------|-----------|
| #3 | Como um usuário, quero excluir as reservas feitas por mim. | 5  |---| Vitor e Lucas |

###Débitos técnicos
| US (User Story) | História | Pontuação | Responsável |
|----------------------|----------|-----------|-------------|
| #2 | Como um administrador, quero consultar todas reservas já efetuadas visualizando todos dados. | 8  | Gustavo e Allan |
| #4 | Como administrador, quero excluir qualquer reserva efetuada. | 8  | Jessica e Vitor |
| #5 | Como um usuário, quero consultar a disponibilidade e as reservas já realizadas em determinado espaço. | 20  | Lucas e Luis, Hugo e Fabíola, Vitor e Hugo, Pedro e Lucas, Fabíola e Elaine, Luis e Hugo |

| TS (Technical Story) | História | Pontuação | Responsável |
|----------------------|----------|-----------|-------------|
| #12 | Como um desenvolvedor, eu quero refatorar o cadastro de criação de reserva para consertar os bugs conhecidos. | 8  | Allan e Vitor e Luis e Fabíola |

As histórias #5 e #12 foram divididas em tarefas e cada uma delas foi devidamente pontuada.

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


#### Tarefas da História #12
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Ajustar confirmação de reserva. | 5  | Allan e Vitor |
| Remodelar campos (dropdowns, data e hora). | 3 | Luis e Fabíola |

## 1.3. Quadro de Conhecimentos
![Quadro de Conhecimentos](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_conhecimento.png) 

## 1.4. Quadro de pareamento
![Quadro de Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_pareamento.png) 

## 1.5. Retrospectiva
|Pontos Positivos|
|----------------|
|Todos os pontos foram entregues!!!|
|Muitos pareamentos|
|Mais integração entre a equipe|

|Pontos Negativos |Causa| Melhoria|
|-----------------|-----|---------|
|Diminuiu o critério de aceitação|Não passar o pep8 em cada branch|Todo Pull Request só será aceito se estiver passando no pep8|
|Reuniões diárias| Desorganização dos horários| Definição de daily presencial toda terça e quinta|

# 2. Resultados:

## 2.1. Burndown
Nessa sprint foi priorizada uma US e o resto foi dívida técnica da sprint anterior. Todos os pontos foram entregues!
![Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_burndown.png)

## 2.2 Velocity
O velocity da equipe foi de 24,3.
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_velocity.png)

## 2.3 Agile EVM
![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_evm.png) 

## 2.4. Qualidade

### 2.4.1 Integração Contínua
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/travis.PNG)

### 2.4.2 Cobertura de Testes
A cobertura de testes subiu de 68% na Sprint 1 para 82% na Sprint 2

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/coveralls.PNG)

<hr>
<b>** Extrato Code Climate para Duplicação, Complexidade e PEP8 abaixo **</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/code_climate.PNG)

<b>** Identificação de Duplicação, Complexidade e PEP8 de acordo com as Issues**</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint2/metrics.PNG)

### 2.4.3 Duplicação de Código
Das 69 issues identificadas pelo code climate, 55 são de código semelhante nos arquivos descritos na tabela acima. Com destaque aos formulários (forms.py). 

### 2.4.4 Complexidade Ciclomática
7 issues de Complexidade Ciclomática identificadas em 3 arquivos.

### 2.4.5 Estilo: PEP8
7 issues de adequação a folha de estilo padrão python PEP8 em 4 arquivos.

### 2.4.6 Ações definidas para melhoria da qualidade
A equipe definiu que nesta sprint focará a melhoria das qualidades nas views.py, pois estas são mais delicadas quanto a arquitetura e demandam mais urgência. Foi criada a TS [#15](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/63)