##1. Introdução
De acordo com o artigo _AgileEVM – Earned Value Management in Scrum Projects_ a AgileEVM ( Agile Earned Value Management ) é uma adaptação da EVM tradicional, agregando valores de custo, cronograma e escopo, tudo isso relacionado com uma baseline planejada no inicio da release.

##1.1 Uso do _AgileEVM_ no projeto SAS
Tomando como base o _AgileEVM_ definido no artigo, a equipe do projeto SAS construiu uma adaptação que melhor refletisse o valor agredo ao longo das sprints e que auxiliasse no monitoramento e controle do escopo, do custo e do tempo no projeto.

Para isso foi definido o uso das métricas descritas na seção seguinte. Além das métricas proposta pelo artigo, foi usada também uma métrica para redimensionar o escopo inicial do projeto (PR - Pontos Replanejados), uma vez que os pontos atribuídos a uma estoria foram replanejados ao longo do projeto. 

##1.2 Métricas - Siglas, Significados e Fórmulas
Sigla | Significado | Descrição/Fórmula
---- | ---- | ----
PC|Pontos Completados|Pontos completos em cada sprint, considerando somente as histórias agregadas ao cliente
PA|Pontos Adicionados|São os pontos adicionados em cada sprint, podendo ser positivos ou negativos
PR|Pontos Replanejados|São os pontos replanejados em cada sprint, podendo ser positivos ou negativos
PRP|Pontos Planejados Da Release|É a soma dos Pontos Planejados Inicialmente para a Release + PA + PR 
RPC|Pontos Completos Na Release|É a soma dos pontos completos na release, de acordo com as sprints(PC).
APC|Porcentagem Completa Real|Pontos Completos Sprint(PC) / Pontos Planejados Totais(PRP)
PPC|Porcentagem Planejada Completa|Número da Sprinte atual / Número total de sprints
BAC|Custo Total Planejado|Pontos Planejados Totais(PRP) * Custo do ponto
AC|Custo Real|Pontos Completos Reais (PCR) * Custo Do Ponto
PV|Valor Planejado|Porcentagem planejada Completa (PPC) * Custo Total Planejado (BAC)
EV|Valor Agregado|Porcentagem Completa Real (APC) * Custo Total Planejado (BAC)
CV|Variação De Custo|Valor Agregado(EV) - Custo Real(AC)
SV|Variação De Cronograma|Valor Agregado(EV) - Valor Planejado(PV)
CPI|Índice de performance de custo|Valor Agregado(EV) / Custo Real(AC)
SPI|Índice de performance planejado|Valor Agregado(EV) / Valor Planejado(PV)

##2. EVM
O EVM do projeto sas pode ser encontrado [aqui](https://docs.google.com/spreadsheets/d/19zNqLpAAX8MbIjVo9yntbyzdDt0A4VzqncRJO_F6Wdg/edit?usp=sharing).

![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/6_evm.png) 
