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

## 2.2 Velocity
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_velocity.png)

## 2.3 Agile EVM


## 2.4. Qualidade

### 2.4.1 Cobertura de Testes

### 2.4.2 Duplicação de Código

### 2.4.3 Complexidade Ciclomática

### 2.4.4 Estilo: PEP8

