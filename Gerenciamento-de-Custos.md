# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|31/08/2016| 1.0|Estrutura Inical |Gustavo |
|04/09/2016| 1.1|Revisão ortográfica e estrutural do documento |Elaine |
|07/09/2016| 1.2| Finalizando documento |Jessica |
|13/09/2016| 1.3| Adequação da estrutura do plano| Pedro|
|19/09/2016| 1.4| Melhora na descrição dos índices | Pedro|
|19/09/2016| 1.5| Adicionando imagens dos custos| Jessica|

## 1.Introdução
O plano a seguir apresenta as estimativas de despêndio e estratégias de monitoramento ao longo do projeto. Os custos foram estimados para refletir da melhor maneira possível o andamento de uma aplicação real. O documento irá apresentar as estimativas de custo, as estratégias de monitoramento e ações para mitigar eventuais adversidades. 

## 2. Planejamento do Custo
### 2.1 Estimativas de custo
#### 2.1.1 Recursos Humanos

O projeto SAS conta com uma equipe de 10 pessoas. O grupo não é homogênio sendo composto por 5 alunos da disciplina de GPP e outros 5 da disciplina de MDS. Porém, os custos foram estimados de forma equânime por se tratarem todos de alunos do curso de engenharia de software da Universidade de Brasília. 

Os trabalhos do projeto serão mensurados em horas, portanto, o custo foi estimado levando-se em consideracão o valor da hora de um estudante de engenharia de software. Esse valor/hora foi estimado, apenas, pelo custo da Universidade de Brasília com o aluno durante um ano; valores gastos por familiares ou pelo próprio aluno foram desconsiderados do cálculo devido a sua dificuldade de mensuração.

A instituição de ensino divulga, em seus relatório gerenciais, o custo anual por aluno. No ano de 2015 o valor aferido foi de R$ 11.300,00 (onze mil e trezentos reais). Um aluno de engeharia de software deve cursar 240 créditos para concluir sua graduação, ou seja, uma média de 48 créditos por ano.  Valendo o crédito na universidade o equivalente a 15 horas aulas pode-se constatar ume média de 720 horas de ensino por ano para cada aluno. O valor/hora dos alunos, então, pode ser estimado dividindo-se o total gasto pela universidade pelo número de horas, o que equivale a R$ 15,30 (quinze reais e trinta centavos). 

O preâmbulo acima juntamente com a estimativa de tempo para cada iteração permite fazermos uma estimativa de gastos detalhada para os recursos humanos, vale lembrar que quando uma atividades está designada a Todos, a mesma custa a quantidade de horas x os 10 alunos, o mesmo acontece para MDS ou GPP, onde o valor do cronograma é multiplicado por 5, como é apresentado na figura abaixo:

![Custo 1](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_It1.png)
![Custo 2](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_It2_1.png) 
![Custo 2.2](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_It2_2.png) 
![Custo 3](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_It3_1.png) 
![Custo 3.2](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_It3_2.png) 
![Custo Release 2](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_Release2.png) 


#### 2.1.2 Insumos
Além dos custos de mão de obra, ainda existe o custo de infraestrutura, que contém o valor da aquisição de cada notebook para desenvolvimento do projeto, internet, espaço físico e energia elétrica como pode ser visto na tabela a seguir:

|Produto / Serviço|Quantidade|Modelo|Fornecedor|Custo Individual|
|-----------------|----------|------|----------|----------------|
| Notebook | 10 unidades | Lenovo G40-80 | Lenovo | R$ 2.299 |
| Internet | 4 meses | 35 MB | OI | R$ 84,90 |
| Espaço | 4 meses | Sala Comercial | WImóveis | R$ 1200 |
| Energia Elétrica | 4 meses | - | CEB | R$ 184|

#### 2.1.3 Custo Total Planejado do Projeto
Considerando todos os custo, temos que o custo total do projeto é:

|Pessoa/Hora|Insumos|Custo Total|
|-----------|-------|-----------|
|R$24.480,00|R$3.767,9|R$28.247,9|

O custo real do projeto pode ser visto no documento de [Acompanhamento de Custo](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Acompanhamento-dos-Custos) do Projeto SAS.

## 3. Monitoramento do Custo

O monitoramento dos custos será realizado através do registro das horas utilizadas para o desenvolvimento das atividades por cada integrante do grupo. Uma vez realizado este levantamento, pode-se encontrar o custo real do projeto. Em referências posteriores, esse valor será tratado por ACWP que é a nomenclatura para custo real no idioma inglês.

Outro item a ser monitorado é o andamento de cada tarefa. Para cada uma delas será descrito, em termos de porcentagem, o quanto foi completado. O andamento da tarefa multiplicado pelo custo planejado é denominado **valor agregado ao projeto**. Ao final de cada iteração será verificado o quanto as tarefas foram completadas e calculado o valor agregado pelo projeto. Seguindo a nomenclatura internacional o valor agregado será apresentado como BCWP, como pode ser visto em  [Acompanhamento de Custo](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Acompanhamento-dos-Custos).
 
## 4. Controle do Custo

O custo real e o monitoramento das atividades permite traduzir o projeto através de indicadores que subsídiam a tomada de decisões estratégicas para o comprimento dos objetivos traçados. Os indicadores usados no projeto são descritos na tabela abaixo:

|Indicador|Descrição|Formula|
|---------|---------|-------|
|Custo Real (CR)|É o custo realizado incorrido no trabalho executado de uma atividade.|----|
|Valor Planejado (VP)|É o orçamento autorizado designado ao trabalho agendado.|----|
|Taxa de Entrega (TE)|É a porcentagem  de conclusão de uma atividade|----|
|Valor Agregado (VA)|É a medida do trabalho executado expressa em termos do orçamento autorizado para tal trabalho.|VA = (VP * TE)/100|
|Variação de Custo (VC)|É a quantidade de déficit ou excedente orçamentário em um determinado momento.|VC = VA – CR|
|Variação de Prazos (VPR)|É a medida de desempenho do cronograma expressa como a diferença entre o valor agregado e o valor planejado.|VPR = VA – VP|
|Índice de Desempenho de Prazos (IDP)|É a medida de eficiência do cronograma expressa como a relação valor agregado/valor planejado.|IDP= VA/VP|
|Índice de Desempenho de Custo (IDC)|É a medida da eficiência de custos dos recursos orçados expressa como a relação valor agregado/custo real.|IDC = VA/CR|


A equipe deve revisar o cronograma e o escopo do projeto todas as vezes que os indicadores Variação de Prazos ou  Índice de Desempenho de Prazos estiverem abaixo de zero. Essa informação deve constar em relatório específico que contemple todas as ações tomadas. O valor de CPI abaixo de zero deve ser comunicado ao cliente e as ações tomadas devem ser documentadas. 