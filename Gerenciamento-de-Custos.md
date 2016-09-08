# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|31/08/2016| 1.0|Estrutura Inical |Gustavo |
|04/09/2016| 1.1|Revisão ortográfica e estrutural do documento |Elaine |
|07/09/2016| 1.2| Finalizando documento |Jessica |

# 1.Introdução
O plano a seguir apresenta as estimativas de despêndio e estratégias de monitoramento ao longo do projeto. Os custos foram estimados para refletir da melhor maneira possível o andamento de uma aplicação real. O documento irá apresentar as estimativas de custo, as estratégias de monitoramento e ações para mitigar eventuais adversidades. 

# 2. Estimativas de custo

## 2.1 Recursos Humanos

O projeto SAS conta com uma equipe de 10 pessoas. O grupo não é homogênio sendo composto por 5 alunos da disciplina de GPP e outros 5 da disciplina de MDS. Porém, os custos foram estimados de forma equânime por se tratarem todos de alunos do curso de engenharia de software da Universidade de Brasília. 

Os trabalhos do projeto serão mensurados em horas, portanto, o custo foi estimado levando-se em consideracão o valor da hora de um estudante de engenharia de software. Esse valor/hora foi estimado, apenas, pelo custo da Universidade de Brasília com o aluno durante um ano; valores gastos por familiares ou pelo próprio aluno foram desconsiderados do cálculo devido a sua dificuldade de mensuração.

A instituição de ensino divulga, em seus relatório gerenciais, o custo anual por aluno. No ano de 2015 o valor aferido foi de R$ 11.300,00 (onze mil e trezentos reais). Um aluno de engeharia de software deve cursar 240 créditos para concluir sua graduação, ou seja, uma média de 48 créditos por ano.  Valendo o crédito na universidade o equivalente a 15 horas aulas pode-se constatar ume média de 720 horas de ensino por ano para cada aluno. O valor/hora dos alunos, então, pode ser estimado dividindo-se o total gasto pela universidade pelo número de horas, o que equivale a R$ 15,30 (quinze reais e trinta centavos). 

O preâmbulo acima juntamente com a estimativa de tempo para cada iteração permite fazermos uma estimativa de gastos detalhada para os recursos humanos, vale lembrar que quando uma atividades está designada a Todos, a mesma custa a quantidade de horas x os 10 alunos, o mesmo acontece para MDS ou GPP, onde o valor do cronograma é multiplicado por 5, como é apresentado na figura abaixo:

![Custo 1](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_Iteracao1.png)
![Custo 2](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-SAS_FGA/img/Custo_Iteracao2.png) 

## 2.2 Insumos
Além dos custos de mão de obra, ainda existe o custo de infraestrutura, que contém o valor da aquisição de cada notebook para desenvolvimento do projeto, internet, espaço físico e energia elétrica como pode ser visto na tabela a seguir:

|Produto / Serviço|Quantidade|Modelo|Fornecedor|Custo Individual|
|-----------------|----------|------|----------|----------------|
| Notebook | 10 unidades | Lenovo G40-80 | Lenovo | R$ 2.299 |
| Internet | 4 meses | 35 MB | OI | R$ 84,90 |
| Espaço | 4 meses | Sala Comercial | WImóveis | R$ 1200 |
| Energia Elétrica | 4 meses | - | CEB | R$ 184|

# 3. Monitoramento

O monitoramento dos custos será realizado através do registro das horas utilizadas para o desenvolvimento das atividades por cada integrante do grupo. Uma vez realizado este levantamento, pode-se encontrar o custo real do projeto. Em referências posteriores, esse valor será tratado por ACWP que é a nomenclatura para custo real no idioma inglês.

Outro item a ser monitorado é o andamento de cada tarefa. Para cada uma delas será descrito, em termos de porcentagem, o quanto foi completado. O andamento da tarefa multiplicado pelo custo planejado é denominado **valor agregado ao projeto**. Ao final de cada interação será verificado o quanto as tarefas foram completadas e calculado o valor agregado pelo projeto. Seguindo a nomeclatura internacional o valor agregado será apresentado como BCWP. 
 
# 4. Estratégias de controle

O custo real e o monitoramento das atividades permite traduzir o projeto através de indicadores que subsídiam a tomada de decisações estratégicas para o comprimento dos objetivos traçados. Os indicadores são descritos na tabela abaixo:

|Indicador | Descrição                       | Explicação                                             |
|----------|---------------------------------|--------------------------------------------------------|
| CV       | Demonstra a variação             | CV > 0, CV < 0, valor agreagado menor que valor gasto  |
| SV       | Demonstra o andamento do projeto | SV > 0, projeto adiantado; SV < 0; projeto atrasado    |
| PSI      | Peformance de prazos             | SPI > 1, Adiantado; SPI = 1, Em dia; SPI < 0, Atrasado | 
| CPI      | Performance dos custos           |   CPI > 1,                                             |

A equipe deve revisar o cronograma e o escopo do projeto todas as vezes que os indicadores SV, SPI estiverem abaixo de zero. Essa informação deve constar em relatório específico que contemple todas as ações tomadas. O valor de CPI abaixo de zero deve ser comunicado ao cliente e as ações tomadas devem ser documentadas. 