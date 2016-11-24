# 1. Introdução

Durante a execução do projeto para a Release 2, foram utilizadas três metodologias adaptadas de modo a atender as necessidades do time e cumprir com o que foi proposto pelas disciplinas MDS e GPP. São estas: Scrum, XP e o Kanban, detalhadas a seguir.

# 2. Scrum

O Scrum é um framework usado desde 1990 para resolver problemas complexos. É importante ter em mente que o Scrum não é um processo ou técnica e sim um framework que permite a inclusão de processos e técnicas.

Este framework consiste em papéis, artefatos e e eventos e tem três bases: transparência, inspeção e adaptação. Os valores do Scrum são comprometimento, coragem, foco, tranparência e respeito. Os que compõem o Time Scrum devem estar comprometidos com esses valores, além de serem auto-organizáveis - ou seja, não precisam de um gerente para dizer o que deve ser feito - e multifuncionais - isto é, possuem qualificação sufuciente para não precisarem de outras equipes para entregar o produto.

## 2.1. Papéis

Os papéis do Scrum são divididos em Scrum Master, Product Owner(PO) e Time de Desenvolvimento. O Scrum Master e o PO no Scrum original não fazem parte do Time de Desenvolvimento, porém, para este projeto, uma das adaptações feita foi a de que eles participariam diretamente do desenvolvimento do software para que tivessem um conhecimento maior acerca do código. 

Outra adaptação é que a cada semana as responsabilidades do Scrum Master e do Product Owner eram assumidas por membros diferentes do time, assim o conhecimento acerca desses papéis foram disseminados entre o grupo.

### 2.1.1. Scrum Master

O Scrum Master é responsável por entender os pricípios do Scrum e garantir que todos o usem corretamente. Também é sua responsabilidade facilitar o desenvolvimento do produto, removendo os impedimentos que houver, e também atuando como mediador, quando necessário.  

A medida que o projeto foi evoluindo o Scrum Master foi perdendo seu valor. Isso dentro da metodologia é algo bom, pois significa que o time foi ficando cada vez mais independente, ao ponto de não precisar de alguém que coordenasse as reuniões, já que todos já sabiam o que precisava ser dito e fazer.

### 2.1.2. Product Owner

O Product Owner é responsável por enteder o que o cliente precisa e priorizar as funcionalidades que devem ser desenvolvidas. Ele é a ponte entre o time de desenvolvimento e o cliente, por isso devem ser feitas reuniões de tempos em tempos.  

No desenvolvimento do SAS essas reuniões ocorriam toda semana às sextas-feiras em que era apresentado à cliente quais a funcionalidades haviam sido implementadas ou estavam sendo terminadas e o cliente, por sua vez, priorizava as funcionalidades mais importantes para ele.

### 2.1.3. Time de Desenvolvimento

O Time de Desenvolvimento é responsável por entregar incrementos funcionais do produto até uma data limite. Ele tem autonomia suficiente para decidir como será feito seu trabalho, sendo que nem o Scrum Master tem autoridade para mudar essa decisão. O ideal, de acordo com o Scrum, é que o time tenha de três a nove integrantes, pois menos que isso a produtividade é pouca e mais do que isso pode haver desorganização.  

O Time de Desenvolvimento foi composto por dez integrantes, que foram evoluindo ao decorrer do projeto como mostra o relatório das Sprints. A decisão de ser um time de dez pessoas foi uma exigência da disciplina, mas mesmo ultrapassando o limite recomendado a auto-organização não prejudicada.

## 2.2. Eventos

### 2.2.1. Reunião Diária
(15minutos)

### 2.2.2. Revisão da Sprint

### 2.2.3. Retrospectiva da Sprint

### 2.2.4. Reunião de Planejamento da Sprint 
(2horas)

## 2.3. Artefatos

### 2.3.1. Backlog do Produto

### 2.3.2. Backlog da Sprint

## 2.4. Métricas

# 3. XP
## 3.1. Automatização
## 3.2. Programação em pares
* Durante essa fase do projeto foi definido que todas as issues seriam feitas por pareamento. Priorizando sempre formar pares de pessoas com mais conhecimento com pessoas com menos conhecimento na linguagens e/ou ferramentas que seriam utilizadas para realizar a issue, para dessa forma poder disseminar a maior quantidade possível de conhecimento dentro da equipe.

**Quadro de Pareamento após a Sprint 0:**
![Quadro de Pareamento da sprint 0](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/0_pareamento.png)

**Quadro de Pareamento após a Sprint 6:**
![Quadro de Pareamento da sprint 6](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_pareamento.png)

## 3.3. TDD
* Apenas a [Sprint 3](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Sprint-3) foi realizada inteiramente em TDD. Basicamente era necessário escrever os testes automatizados, teste unitário e teste aceitação, de uma melhoria ou nova funcionalidade. Em seguida, o código da funcionalidade seria desenvolvido, em *baby-steps*, para validar a funcionalidade criada.

* Essa sprint resultou em uma significativa melhora do time em testes de aceitação e testes unitários.

**Quadro de Conhecimento após a Sprint 2:**
![Quadro de Conhecimentos sprint 2](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/2_conhecimento.png)

**Quadro de Conhecimento após a Sprint 3:**
![Quadro de Conhecimento sprint 3](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/3_conhecimento.png)

## 3.4. Integração Contínua
## 3.5. Teste de Aceitação
* Para cada *User Story* deveriam ser feitos testes aceitação para a validação do sistema e para o cliente entender como será o funcionamento da *US*
* As para o finalizamento da issue é necessário que os teste de aceitação estivessem funcionando corretamente.

## 3.6. Refatoração

Para refatoração foram utilizadas as métricas geradas pelo cloud climate em relação a: folha de estilo (pep8), duplicação e complexidade de código. Arquivos com nota F tiveram criadas estórias técnicas de refatoração no repositório, para que suas qualidades aumentassem. Outros arquivos também foram melhorados a medida que se produzia código e o time percebia uma possível melhora, não sendo necessário estar trabalhando numa estória relacionada ao método refatorado. Os exemplos a seguir mostram issues que auxiliam na orientação da refatoração. 

![Gráfico das Métricas](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/qualidade_r2.jpg)

# 4. Kanban

Para organização do fluxo de trabalho do time, montou-se um quadro kanban:

![Kanban](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/kanban.png)

Cada coluna representa, respectivamente:

* Backlog: Contendo todas as issues ainda não entregues do produto.

* TODO (Sprint Backlog): Contendo todas as issues ainda não entregues da sprint.

* DOING: Contendo todas as issues que são trabalhadas no momento.

* Test: Contendo todas as issues que estão em fase de teste.

* Done: Contendo todas as issues já entregues.

Em cada  issue é possível consultar os responsáveis por esta, sendo que o responsável não precisa realizá-la sozinho, podendo recorrer a qualquer membro do time para auxiliá-lo. Caso haja mais de um responsável, o pareamento deve ser priorizado entre os responsáveis, porém não é obrigatório, podendo da mesma forma realizá-la com outros membros.

Na issue também é possível consultar suas respectivas tags, que podem ser alteradas por qualquer membro do time, caso seja necessário. Abaixo estão representadas as tags utilizadas.

![Tags](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/issues_labels.png)

