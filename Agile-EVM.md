##1. Introdução
De acordo com o artigo _AgileEVM – Earned Value Management in Scrum Projects_ a AgileEVM ( Agile Earned Value Management ) é uma adaptação da EVM tradicional, agregando valores de custo, cronograma e escopo, tudo isso relacionado com uma baseline planejada no inicio da release.

##1.1 Siglas, Significados e Fórmulas
Sigla | Significado | Descrição/Fórmula
---- | ---- | ----
PP|Pontos Planejados|Pontos planejados para cada sprint, planejados desde de o planejamento inicial da release
PC|Pontos Completados|Pontos completos em cada sprint, considerando somente as histórias agregadas ao cliente
PCR|Pontos Completos Reais|Pontos completos na sprint, considerando também os pontos relacionados ao esforço da história, mesmo que a história não seja terminada
PA|Pontos Adicionados|São os pontos adicionados em cada sprint, podendo ser positivos ou negativos
PRP|Pontos Planejados Da Release|É a soma dos pontos planejados para toda a release, sendo eles imutáveis no decorrer da mesma
RPC|Pontos Completos Na Release|É a soma dos pontos completos na release, de acordo com as sprints(PC).
PPC|Porcentagem Completa Planejada| Pontos Planejados Sprint(PP) / Pontos Planejados Totais(PRP)
APC|Porcentagem Completa Real|Pontos Completos Sprint(PC) / Pontos Planejados Totais(PRP)
BAC|Custo Total Planejado|Pontos Planejados Totais(PRP) * Custo do ponto
AC|Custo Real|Pontos Completos Reais (PCR) * Custo Do Ponto
PV|Valor Planejado|Porcentagem planejada Completa (PPC) * Custo Total Planejado (BAC)
EV|Valor Agregado|Porcentagem Completa Real (APC) * Custo Total Planejado (BAC)
CV|Variação De Custo|Valor Agregado(EV) - Custo Real(AC)
SV|Variação De Cronograma|Valor Agregado(EV) - Valor Planejado(PV)
CPI|Índice de performance de custo|Valor Agregado(EV) / Custo Real(AC)
SPI|Índice de performance planejado|Valor Agregado(EV) / Valor Planejado(PV)
ETC|Estimate To Complete|1/Indice De Performance De Custo(CPI) * (Custo Total Planejado(BAC) – Valor Agregado(EV))
EAC|Estimate At Complete|Custo Total Planejado(BAC)/Indice De Performance De Custo(CPI)

##2. EVM
O EVM do projeto sas pode ser encontrado [aqui](https://docs.google.com/spreadsheets/d/1qEAfjiwK28bGGbYWuX1VVXOmoH-pnMCV1tzF2k8UKm4/edit?usp=sharing).