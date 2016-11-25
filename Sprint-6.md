# 1. Planejamento da Sprint
Nessa sprint foi priorizada uma nova demanda solicitada pela cliente, e os débitos técnicos.

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Allan        | Jessica     |<ul><li>Elaine</li><li>Fabiola</li><li>Lucas</li><li>Luís</li><li>Pedro</li><li>Vitor</li><li>Gustavo</li> <li>Hugo</li>  |

## 1.2. Backlog

| US (User Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-----------|-----------|
|#18|Como administrador, quero cadastrar tags (#) para depois conseguir gerar um relatório de acordo com as tags selecionadas.|---|20|Fabíola, Vítor, Luis|

###1.2.2 Débitos Técnicos

| US (User Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-----------|-----------|
|#13| Como administrador, quero selecionar uma engenharia ao criar uma reserva, para ter o controle por curso.|---|2|Elaine e Pedro|
|#14| Como administrador, quero poder pesquisar uma reserva pelo nome do responsável, para conseguir localizar em qual sala está um professor.|---|5|Hugo e Lucas|

| TS (Technical Story) | História | Pontuação |Nova Pontuação| Responsável |
|----------------------|----------|-----------|-------------|--------------|
|#20|Como desenvolvedor, quero facilitar a criação de reserva possibilitando selecionar sala sem ser obrigatório a seleção de prédio.|---|5|Gustavo e Jessica|
| #16 | Como desenvolvedor, eu quero refatorar a criação de reservas, para ficar mais intuitivo. |8|---|Gustavo|

#### Tarefa Pendente da História #16
| Tarefa | Pontuação | Responsável |
|--------|-----------|-------------|
| Adaptar JavaScript| 4 | Gustavo |


## 1.3. Quadro de Conhecimentos
![Quadro de Conhecimentos](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_conhecimento.png) 

## 1.4. Quadro de pareamento
![Quadro de Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_pareamento.png) 

## 1.5. Retrospectiva
|Pontos Positivos|
|----------------|
|Alto nível de conhecimento|
|Foi possível terminar a US criada pela cliente na sprint passada|
|Alto entrosamento da equipe|

|Pontos Negativos |Causa| Melhoria|
|-----------------|-----|---------|
|Demora para começar a programar|Final de semestre|---|
|TS inacabada|Falta de tempo|---|


# 2. Resultados:

## 2.1. Burndown
![Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_burndown.png)

## 2.2 Velocity
O velocity desta sprint foi de **28,6 pontos**. Esse velocity é a média de todas as sprints. A tabela utilizada par ao cálculo do velocity e o gráfico podem ser vistos abaixo.

![VelocityTab](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_velocityTab.png)
![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_velocity.png)

## 2.3 Agile EVM
![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_evm.png)

**OBS.** As descrições e fórmulas das siglas apresentadas na tabela acima estão devidamente explicitadas [aqui](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Agile-EVM). Neste mesmo link pode ser encontrada a tabela de EVM completa do projeto.

Foram planejados 20 pontos, além da divida técnica,  e entregues 31.

O RPC (Pontos Completos Na Release) ficou em 169, o APC (Porcentagem Completa Real) em 130%.

Foram adicionados 33 ponto novos ao projeto, PA (Pontos Adicionados) = 20, todos os pontos planejados para a sprint.
 

## 2.4. Qualidade

### 2.4.1 Integração Contínua
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint6/travis.PNG)

### 2.4.2 Cobertura de Testes
A cobertura de testes aumentou 1% nesta sprint, 92%.

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint6/coveralls.PNG)

<hr>
<b>** Extrato Code Climate para Duplicação, Complexidade e PEP8 abaixo **</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint6/code_climate.PNG)

<b>** Identificação de Duplicação, Complexidade e PEP8 de acordo com as Issues**</b>
![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint6/metrics.PNG)

### 2.4.3 Duplicação de Código
Houve severa redução na quantidade de código duplicado, mais de 50% de redução em comparação com a sprint anterior. As issues remanescentes serão avaliadas sua complexidade de resolução.

### 2.4.4 Complexidade Ciclomática
8 issues de complexidade identificadas. Estas issues são prioritárias para resolução.

### 2.4.5 Estilo: PEP8
Nesta sprint, dois arquivos foram identificados: booking/models.py e sas/steps/steps.py


### 2.4.6 Ações definidas para melhoria da qualidade
Esta semana contará com um mutirão de ação sob as últimas issues, conforme identificadas nesta sprint. Todas as issues de complexidade e de estilo serão resolvidas, atacadas individualmente conforme indicadas pelo code climate. As issues de duplicação serão avaliadas conforme possibilidade de serem resolvidas, muitas delas só se resolvem com modificações arquiteturais severas, o que não justifica o esforço.