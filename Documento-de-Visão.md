# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|20/08/2016 |1.0 |Introdução |Lucas |
|20/08/2016 |1.1 |Visão Geral do Produto |Vítor

# Introdução
  
Este documento tem como objetivo definir o escopo, a proposta, os recursos do produto, o problema a ser resolvido, quem terá acesso ao produto, assim como o tipo de acesso. O cliente do sistema realiza a locação de salas de forma manual. O objetivo do projeto é criar um sistema que automatize esse processo, evitando erros, como duas salas locadas para a mesma pessoa no mesmo horário,  tornando-o ágil.

# Visão Geral do Produto

## Perspectiva do Produto

No atual contexto do ambiente acadêmico da Universidade de Brasília, constata-se uma crescente necessidade por um sistema que facilite a alocação de salas por discentes, docentes e demais integrantes do corpo acadêmico – seja para apresentações de Trabalhos de Conclusão de Curso, aulas de monitoria ou tutoria, dentre outros – visto que, hoje, tal procedimento demanda um longo processo e burocracia. 

## Sumário de Capacidades

Tabela 1 – Benefícios do Usuário e Recursos de Suporte

|Benefícios do Usuário|Recursos de Suporte|
|---------------------|-------------------|
|Alocação da sala feita mais rapidamente.|O processo de análise do pedido, verificando se a sala no horário requerido está livre, é otimizado.|
|Não há choque de horários (mais de uma sala reservada para a mesma pessoa no mesmo horário ou uma sala reservada para mais de uma pessoa no mesmo horário).|O sistema analisa se a sala já possui reservas no horário ou se o usuário já possui uma reserva neste horário, impedindo outra reserva.|

## Suposições e Dependências

O sistema será utilizado pelo usuário através da internet, logo, há custos de hospedagem. Assim, supõe-se que o cliente arcará com estes valores para que o sistema permaneça online.


