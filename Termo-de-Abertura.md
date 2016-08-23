# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|18/08/2016|1.0|Criação da estrutura inicial. Adição dos tópicos 2 e 3|Allan, Elaine, Gustavo, Jessica e Pedro|
|19/08/2016|1.1|Revisão dos tópicos. Adição do tópico 9 (Prazos). Adição de conteúdo nos tópicos 1, 4 e 9.|Allan|
|19/08/2016|1.2|Adição de conteúdo nos tópicos 5 e 6.|Elaine|
|20/08/2016|1.3|Atualização do tópico 9 (Prazos).|Allan|
|21/08/2016|1.4|Adição dos tópicos 8, 10 e 11| Jessica|
|21/08/2016|1.5|Adição do tópico 7| Gustavo|
|21/08/2016|1.6|Revisão em todo documento. Alterações nos tópicos: 6, 8, 10 e 11| Allan|
|22/08/2016|1.7|Revisão ortográfica em todo documento.| Elaine|

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
#### 6.1 Restrições:

1. O Sistema de Alocação de Salas está voltado exclusivamente para a plataforma web.
2. O prazo para desenvolvimento do projeto é de aproximadamente 16 semanas.
3. Não há disponibilidade de verba para investimento em qualquer aquisição.
4. As equipes de gerência e desenvolvimento são limitadas, não havendo mão de obra extra para apoio.

#### 6.2 Riscos:

1. Diminuição das equipes de desenvolvimento e gerência: integrantes podem abandonar a disciplina.
2. Ocorrência de problemas de saúde (ou afins) nos integrantes, causando indisponibilidade ou perda de eficiência. 
3. Inabilidade dos integrantes quanto ao uso da linguagem de programação e/ou ao framework utilizados para o desenvolvimento.
4. A ferramenta desenvolvida apresentar falhas ao não alocar corretamente os espaços da Universidade de Brasília - FGA, provocando choques de agendamento.
5. As informações da grade de horários não serem informadas acertadamente.
6. O software desenvolvido não seja útil a instituição, apesar de todo o esforço gasto no projeto.
7. O software não esteja totalmente construído e testado dentro do prazo estipulado.
8. Falhas/Defeitos em equipamentos e outros recursos necessários ao desenvolvimento (Laptops, internet, etc.)
9. Indisponibilidade ou contratempos no uso do espaço físico de desenvolvimento do projeto. 

## 7. Estimativa de Custo

A estimativa de custo tem como finalidade apresentar para os integrantes da equipe e para os outros alunos da disciplina o custo envolvido no desenvolvimento de um software real. As estimativas usam dados coletados na internet em sites especializados como Catho, WImovéis, entre outros. Os web sites citados fornecem dados de custo de profissionais e matériais que possibilitam estimar o custo do projeto. 

### 7.1 Custo da mão de obra.

Os dados aqui apresentados foram retirados do site Catho Empresas e só leva em consideração a média salarial oferecida para o [desenvolvedor júnior Python](http://www.catho.com.br/salario/action/site/area_geral.php?state=salario&id_area_especifica=40&id_area_geral=16&id_cargo=7538) e de [Gerente de Tecnologia da Informação](http://www.catho.com.br/salario/pesquisa-salarial/cargos-salarios/sistemas-informatica-internet/tecnologia-da informacao-ti/gerente-de-tecnologia-da-informacao) oferecida no web site. Portanto, não será considerados custos trabalhistas que devem ser pagos no Brasil.

| Equipe MDS       |                               |         |
|------------------|-------------------------------|---------|
| Dias trabalhados | Média estimada de hrs diárias | Total   |
| 109              | 2                             | 218     |
| Salario Médio    | Hora Média                    | Total   |
| 2079,62          | 12,99                         | 2833,48 |
|                  | Total Grupo                   | 11333,92|

| Equipe GPP       |                               |         |
|------------------|-------------------------------|---------|
| Dias trabalhados | Média estimada de hrs diárias | Total   |
| 109              | 2                             | 218     |
| Salario Médio    | Hora Média                    | Total   |
| 8628,52          | 53,92                         | 11756,35|
|                  | Total Grupo                   | 58359,36|

### 7.2 Insumos

O desenvolvimento de um projeto de software necessita de equipamentos como computadores e internet para ser executado. Os custos com alguns desses itens foram estimados com a finalidade de se chegar ao custo 'total do projeto. Os itens estimados são: [computadores](http://www.dell.com/br/p/inspiron-15-5558-laptop/pd?oc=cai5558w101712358bbbrp171w&model_id=inspiron-15-5558-laptop) e [internet] (https://assine.vivo.com.br/combos/combos-2-em-1).
 
| Item       | Qtde/Tempo | Valor   | Total    |
|------------|------------|---------|----------|
| Computador | 10         | 2079,00 | 20790,00 |
| Internet   | 4          | 149,8   | 599,2    |


### 7.3 Aluguel

Uma empresa precisaria dispor de um local para o encontro dos seus membros. Uma busca em [web sites de aluguel de imóveis](http://www.wimoveis.com.br/imovel/aluguel-sala-comercial-gama-df-quadra-17-1354260) no Gama-DF possibilitou estimar um valor para o custo de alguel para uma sala comercial, onde os membros poderiam se reunir 
para desenvolver o produto.

| Item       | Tempo(Meses)| Valor   | Total    |
|------------|-------------|---------|----------|
| Aluguel     | 4           | 1200,00 | 4800,00  |

### Custo Total

Os itens estimados possibilitam mostrar que o projeto teria um custo aproximado de R$ 95.882,50. O valor pode ser maior ou menor devido a outras variáveis não consideradas, como encargos trabalhistas, energia elétrica, água, dentre outros. 

## 8. Estratégia de Comunicação
São realizadas reuniões presenciais semanais aos sábados, às 14h, no espaço da Faculdade UnB Gama. Em adição à comunicação presencial, tem-se:
1. Comunicação entre MDS e GPP via grupo no aplicativo WhatsApp.
2. Comunicação equipe de GPP via grupo no aplicativo Telegram.

## 9. Prazos
O projeto é iniciado em 09/08/2016 com data prevista para término em 29/11/2016, totalizando 16 semanas (109 dias). São conhecidos dois marcos principais do projeto:
* **Release 1** - 24 e 25/09/2016:
Com duração de 6 semanas (41 dias). Na data definida tem-se uma apresentação caracterizada pela demonstração formal do progresso do projeto sob uma ótica de gerenciamento utilizando metodologia tradicional. Neste ponto, o projeto deverá ter avançado consideravelmente prezando o monitoramento e controle das características de Qualidade, Custo e Tempo do projeto,conforme guia [PMBOK](https://brasil.pmi.org/brazil/PMBOKGuideAndStandards.aspx) edição 5.

* **Release 2** - 29/11 e 01/12/2016:
Com duração de 10 semanas (63 dias). Já na data da release 2, pretende-se demonstrar o progresso do projeto utilizando uma metodologia de gerenciamento ágil de projeto, SCRUM e eXtreme Programming (XP). 

## 10. Stakeholders
### 10.1 Envolvidos
|Nome |Descrição |Responsabilidade |
|---|---|---|
|Gerentes de Projeto | Equipe de alunos de Gestão de Projetos e Portfólio de Software | Gerenciar o projeto |
|Desenvolvedores | Equipe de alunos de Métodos de Desenvolvimento de Software | Desenvolver o sistema |
|Clientes | Coordenadores dos cursos da Faculdade; Demais usuários vinculados a Universidade | Estabelecer e validar os requisitos |

### 10.2 Usuários
|Nome |Descrição |Responsabilidade | Representante|
|---|---|---|---|
|Administrador | Administrador do sistema | Reservar salas e controlar as reservas | Coordenadores dos cursos |
|Usuário | Usuário final do sistema | Solicitar a reserva de salas | Professores, estudantes, técnicos administrativos e demais integrantes do Corpo Acadêmico |

## 11. Tecnologias Utilizadas
1. Github - Repositório para código e documentação oficial. (https://www.github.com/)
2. Google Drive - Compartilhamento e organização de documentos. (https://drive.google.com/)
3. Python 3.5 - Linguagem de programação. (https://www.python.org/)
4. Django 1.10 - Framework. (https://www.djangoproject.com/)
5. Flake8 3.1 - Padronização de estilo de programação visando qualidade de código. (http://flake8.pycqa.org/)
