# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|18/08/2016|1.0|Criação da estrutura inicial. Adição dos tópicos 2 e 3|Allan, Elaine, Gustavo, Jessica e Pedro|
|19/08/2016|1.1|Revisão dos tópicos. Adição do tópico 9 (Prazos). Adição de conteúdo nos tópicos 1, 4 e 9.|Allan|
|19/08/2016|1.2|Adição de conteúdo nos tópicos 5 e 6.|Elaine|
|20/08/2016|1.3|Atualização do tópico 9 (Prazos).|Allan|
|21/08/2016|1.4|Adição dos tópicos 8, 10 e 11| Jessica|

## 1. Introdução
Este documento formalmente inicia o projeto de construção do Sistema para Alocação de Espaços para a Faculdade UnB Gama. Aqui é especificado o trabalho que este projeto visa realizar, a oportunidade de negócio identificada, o escopo de atuação, os indivíduos direta e indiretamente afetados, características de riscos, restrições e de custos, entregáveis, prazos e as ferramentas utilizadas no processo de desenvolvimento. Tais descrições visam elucidar a viabilidade do projeto.

## 2. Descrição do Projeto
   O SAS é um Sistema de Alocação de Salas para a Faculdade do Gama (FGA) da Universidade de Brasília (UnB), desenvolvido para plataforma web que tem por finalidade automatizar a reserva de espaços pelos docentes, discentes e demais interessados.

## 3. Propósito do Projeto
* Facilitar o processo de reivindicação de espaços internos da Universidade;
* Reduzir a carga de trabalho manual atualmente realizada neste processo;
* Possibilitar a geração de relatórios de utilização dos espaços;
* Otimizar o uso da infraestrutura interna da Universidade;

## 4. Oportunidade de Negócio
Atualmente a coordenação da Universidade, mais especificamente da UnB Gama, realiza o controle do uso dos espaços, salas em especial, através de uma planilha eletrônica manualmente confeccionada e mantida. Tal situação demanda alta carga de tempo e esforço para a tarefa de administração do uso dos espaços durante o decorrer do ano, especialmente durante a definição das salas para os cursos do semestre letivo.

## 5. Escopo
O escopo do SAS, Sistema de Alocação de Salas, se baseia na funcionalidade principal de exibir um mapa de salas, inicialmente da Universidade de Brasília - Faculdade Gama (FGA), onde alocações de diversas naturezas poderão ser realizadas, sendo elas de disciplinas, através dos coordenadores, e de monitorias, reuniões ou quaisquer outras atividades extra-curriculares, através de alunos, técnicos e funcionários administrativos. Este projeto possui a finalidade de facilitar a reserva dos espaços da instituição, assim como evitar possíveis colisões. Outras funcionalidades abrangem a exibição de porcentagens de lotação através de barras de progresso, além de visualização e impressão de tabelas de horários internos referentes a cada sala.

## 6. Restrições e Riscos
#### 6.1 O projeto SAS possui as restrições listadas abaixo:

1. O Sistema de Alocação de Salas está voltado exclusivamente para a plataforma web.
2. O prazo para desenvolvimento do projeto é de aproximadamente 16 semanas.

#### 6.2 O projeto SAS possui os seguintes riscos:

1. Integrantes do grupo abandonarem a disciplina.
2. Integrantes do grupo não se adaptarem a linguagem de programação e/ou ao framework.
3. O SAS não alocar corretamente os espaços da Universidade de Brasília - FGA, provocando colisões.
4. As informações da grade de horários não serem informadas acertadamente.
5. Apesar de todo o esforço gasto no projeto, o mesmo não seja útil a instituição.
6. Que os documentos criados no projeto não estejam disponíveis aos brasileiros.

## 7. Estimativa de Custo

## 8. Ferramentas de Comunicação
1. Comuncação entre MDS e GPP via WhatsApp.
2. Comunicação equipe de GPP via Telegram.

## 9. Prazos
O projeto é iniciado em 09/08/2016 com data prevista para término em 29/11/2016, totalizando 16 semanas (109 dias). São conhecidos dois marcos principais do projeto:
* **Release 1** - 24 e 25/09/2016:
Com duração de 6 semanas (41 dias). Na data definida tem-se uma apresentação caracterizada pela demonstração formal do progresso do projeto sob uma ótica de gerenciamento utilizando metodologia tradicional. Neste ponto, o projeto deverá ter avançado consideravelmente prezando o monitoramento e controle das características de Qualidade, Custo e Tempo do projeto,conforme guia [PMBOK](https://brasil.pmi.org/brazil/PMBOKGuideAndStandards.aspx) edição 5.

* **Release 2** - 29/11 e 01/12/2016:
Com duração de 10 semanas (63 dias). Já na data da release 2, pretende-se demonstrar o progresso do projeto utilizando uma metodologia de gerenciamento ágil de projeto, SCRUM e eXtreme Programming (XP). 

## 10. Stakeholdes
### 10.1 Envolvidos
|Nome |Descrição |Responsabilidade |
|---|---|---|
|Gerentes de Projeto | Alunos de GPP | Gerenciar o projeto |
|Desenvolvedores | Alunos de MDS | Desenvolver o sistema |
|Clientes | Coordenadores | Estabelecer os requisitos |

### 10.2 Usuários
|Nome |Descrição |Responsabilidade | Representante|
|---|---|---|---|
|Administrador | Administrador do sistema | Reservar salas e controlar as reservas | Coordenadores dos cursos |
|Usuário | Usuário final do sistema | Solicitar a reserva de salas | Professores, estudantes, técnicos administrativos e demais integrantes do Corpo Acadêmico |

## 11. Tecnologias Utilizadas
1. Github - Repositório para código e documentação.
2. Google Drive - Compartilhamento e organização dos documentos.
3. Python - Linguagem de programação.
4. Django - Framework.
5. Flake 8 - Qualidade de código.
