# 1. Planejamento da Sprint
Todas as estórias foram criadas pela Carla, durante a apresentação do sistema.

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Luís        | Elaine      |<ul><li>Allan</li><li>Fabiola</li><li>Lucas</li><li>Luís</li><li>Pedro</li><li>Vitor</li>  |

## 1.2. Backlog

| US (User Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-----------|-----------|
| #8 | Como um visitante, quero consultar as perguntas frequentes do sistema para sanar dúvidas sobre o sistema. | 3 |1|Elaine e Luís|
|#12| Como usuário, eu quero selecionar qual a Engenharia que curso durante o meu cadastro, para o administrador ter um controle de reservas por Engenharia.|---|3|Lucas e Luís|
|#13| Como administrador, quero selecionar uma engenharia ao criar uma reserva, para ter o controle por curso.|---|2|Elaine e Pedro|
|#14| Como administrador, quero poder pesquisar uma reserva pelo nome do responsável, para conseguir localizar em qual sala está um professor.|---|5|Hugo e Lucas|
|#15|Como administrador, quero cadastrar datas de início e fim para um semestre e ao criar uma reserva selecionar o semestre ao invés das datas, para agilizar o processo de criar reserva.|---|3|Fabíola e Hugo|
|#16| Como administrador, quero excluir apenas um horário específico da reserva, para aproveitar melhor os espaços da FGA.|---|5|Vitor e Gustavo|
|#17| Como administrador, quero visualizar a capacidade de cada sala ao fazer a reserva, para conseguir alocar as disciplinas melhor.|---|3|Allan e Jessica|


| TS (Technical Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-------------|-------------|
|#18| Como desenvolvedor, eu quero melhorar as colunas das datatables, incluindo dia da semana e horário, para entender melhor as reservas.|---|5|Allan e Jessica|
|#19|Como desenvolvedor, eu quero mostrar a tabela das consultas mesmo sem existir nenhuma reserva nos filtros selecionados, para possibilitar a inclusão de uma reserva.|---|2|Luís e Vítor|
|#20|Como desenvolvedor, quero facilitar a criação de reserva possibilitando selecionar sala sem ser obrigatório a seleção de prédio.|---|5|Gustavo e Jessica|

###1.2.2 Débitos Técnicos
| TS (Technical Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-------------|--------------|
| #16 | Como desenvolvedor, eu quero refatorar a criação de reservas, para ficar mais intuitivo. |8|---|Gustavo|

#### Tarefa Pendente da História #16
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Adaptar JavaScript| 4 | Gustavo |


## 1.3. Quadro de Conhecimentos
![Quadro de Conhecimentos](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/5_conhecimento.png) 

## 1.4. Quadro de pareamento
![Quadro de Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/5_pareamento.png) 

## 1.5. Retrospectiva
|Pontos Positivos|
|----------------|
| Correção de bugs |
| Melhorias para satisfazer a cliente |

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
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/5_velocity.png)

## 2.3 Agile EVM
![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/5_evm.png) 

## 2.4. Qualidade

### 2.4.1 Integração Contínua
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint5/travis.PNG)

### 2.4.2 Cobertura de Testes
A cobertura de testes permaneceu em 87% na Sprint 4.

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint5/coveralls.PNG)

<hr>
<b>** Extrato Code Climate para Duplicação, Complexidade e PEP8 abaixo **</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint5/code_climate.PNG)

<b>** Identificação de Duplicação, Complexidade e PEP8 de acordo com as Issues**</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint5/metrics.PNG)

### 2.4.3 Duplicação de Código


### 2.4.4 Complexidade Ciclomática

### 2.4.5 Estilo: PEP8

### 2.4.6 Ações definidas para melhoria da qualidade
