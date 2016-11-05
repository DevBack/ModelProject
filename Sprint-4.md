# 1. Planejamento da Sprint
Não conseguimos entrar em contato com a Carla, por isso as estórias foram priorizadas pelo time na reunião de planejamento.

<b>
Em virtude do tempo de duração de sprint, definido em uma semana, estar se mostrando insuficiente à conclusão de User Stories devido à carga de trabalho demandada, a equipe definiu fazer uma subdivisão dos pontos definidos às User Stories em tarefas de forma a realizar o acompanhamento (Burndown, Velocity, EVM) mais granular, preciso e com menos dependências, sem comprometer a produtividade da equipe já habituada à agilidade semanal de produção.
</b>

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Lucas       | Jessica      |<ul><li>Allan</li><li>Elaine</li><li>Fabiola</li><li>Gustavo</li><li>Hugo</li><li>Luís</li><li>Pedro</li><li>Vitor</li>  |

## 1.2. Backlog

| US (User Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-----------|-----------|
|#7|Como um administrador, quero aprovar reservas de laboratórios solicitadas pelo corpo acadêmico para ter um maior controle sobre quem utiliza os laboratórios.|13|8|Pedro e Fabíola|
|#10|Como usuário, eu quero reservar um espaço a partir da tabela de ocupação para utilizar a sala.|---|8|Hugo e Luis|
|#11|Como administrador, eu quero designar um responsável pelas reservas que eu cadastrar para manter o controle da reserva.|---|13|Lucas e Vitor|

| TS (Technical Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-------------|--------------|
|#17 | Como desenvolvedor, eu quero fazer deploy para colocar o SAS em produção.|---| 2 | Gustavo|

As histórias de usuário US#7 e US#10 foram divididas em tarefas, as quais são:

#### Tarefas da História #7
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Atualizar o sistema para comportar estrutura de status da reserva | 6 | Fabíola e Pedro |
| Criar página de gerenciamento de reservas pendentes | 2 | Fabíola e Pedro |


#### Tarefas da História #10
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Modificar views para cada filtro | 2 | Hugo e Luís |
| Criar a modal de reserva | 1 | Hugo e Luís |
| Modificar forms para o newbooking na modal | 1 | Hugo e Luís |
| Criar template tags necessárias | 3 | Hugo e Luís |
| Adaptar template table | 1 | Hugo e Luís |

###Débitos técnicos
| TS (Technical Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-------------|--------------|
| #10 | Como um desenvolvedor, eu quero realizar as validações necessárias da criação de reserva para garantir a consistência dos dados inseridos.|8|5|Elaine|
| #15 | Como um desenvolvedor, eu quero refatorar as views, para melhorar a qualidade do código. |13|---|Allan|
| #16 | Como desenvolvedor, eu quero refatorar a criação de reservas, para ficar mais intuitivo. |8|---|Gustavo|

As estórias técnicas TS#15 e TS#16 foram concluídas parcialmente, e como foi decidido anteriormente a equipe está acompanhando as tarefas, portanto seguem as tarefas que estão faltando dessas estórias para essa sprint.

#### Tarefa Pendente da História #15
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Diminuir complexidade da User View | 3 | Allan |

#### Tarefa Pendente da História #16
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Adaptar JavaScript| 4 | Gustavo |

## 1.3. Quadro de Conhecimentos
![Quadro de Conhecimentos](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/4_conhecimento.png) 

## 1.4. Quadro de pareamento
![Quadro de Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/4_pareamento.png) 

## 1.5. Retrospectiva
|Pontos Positivos|
|----------------|
| Aumento da produtividade da equipe |
| Conhecimento de frontend adquirido |
| Maior preocupação com qualidade |

|Pontos Negativos |Causa| Melhoria|
|-----------------|-----|---------|
| Demora para começar a queimar pontos | Provas e trabalhos de outras disciplinas | Organizar melhor as tarefas diárias para conseguir fazer um pouco de tudo |
| Redução na frequência de consulta do coach | Demora no início da realização das histórias/tarefas, ou seja, demora na descoberta de dúvidas | Começar a realização o quanto antes |
| Daily relativamente demorada | Falta de foco na reunião | Aumento do comprometimento com a daily | 
| Master desatualizada e quebrada | Falta de merge com a master sempre que a dev está estável | Aumentar frequência de merges com a master |
| Cobertura ainda está abaixo do mínimo | Falta de alguns testes de funcionalidades "antigas" | Aumentar cobertura de teste |

# 2. Resultados:

## 2.1. Burndown
![Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/4_burndown.png)

## 2.2 Velocity
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/4_velocity.png)

## 2.3 Agile EVM


## 2.4. Qualidade

### 2.4.1 Integração Contínua
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint4/travis.png)

### 2.4.2 Cobertura de Testes
A cobertura de testes permaneceu em 87% na Sprint 4.

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint4/coveralls.png)

<hr>
<b>** Extrato Code Climate para Duplicação, Complexidade e PEP8 abaixo **</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint4/code_climate.png)

<b>** Identificação de Duplicação, Complexidade e PEP8 de acordo com as Issues**</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint4/metrics.png)

### 2.4.3 Duplicação de Código


### 2.4.4 Complexidade Ciclomática

### 2.4.5 Estilo: PEP8

### 2.4.6 Ações definidas para melhoria da qualidade
