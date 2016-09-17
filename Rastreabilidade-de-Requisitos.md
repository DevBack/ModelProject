# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|15/09/2016|1.0|Criação do Documento|Pedro|
|17/09/2016|1.1||Pedro|

## 1. Introdução
Este documento define as rastreabilidade dos requisitos levantados para o sistema SAS, identificando o Problema e relacionando-o com as Necessidades, Requisitos e Casos de Usos levantados para o sistema.  

## 2. Definição do Problema

|ID|O Problema|Afeta|Cujo Impacto|Uma boa Solução seria|
|-------------|----------|-----|------------|---------------------|
|P1|O problema de dificuldade na alocação de espaço na Universidade de Brasília|Que afeta a comunidade acadêmica. (Em especial os responsáveis pela alocação de espaços para disciplinas - Coordenadores de Cursos)|Cujo impacto é o grande esforço demandado para alocar os espaços da universidade para as atividades acadêmicas|Uma boa solução seria a implantação de um sistema que automatizasse esse processo|

## 2. Necessidade

|ID|Necessidade|Solução atual|Solução proposta|
|-------------|-----------|-------------|----------------|
|N1|Reservar espaços para disciplinas|Uso de planilhas|Sistema que permita ao coordenador reservar espaços e atribuir a um responsavel|
|N2|Reservar espaços esporadicamente|Uso de documentos para comunicar a autorização do uso do espaço|Sistema que permita que ao corpo acadêmico reservar um espaço, ou solicitar a reserva em casos especiais.|
|N3|Consulta de disponibilidade de espaços|Uso de planilhas|Sistema que permita a consulta dos espaços e de suas disponibilidades em um determinado periodo|
|N4|Gerenciamento de responsáveis por espaços alocados|Uso de Planilhas|Sistema que permita gerenciar os responsáveis por alocação|

##3. Requisitos do Sistema 

|ID|Requisito|
|-------------|---------|
|RF01|O sistema deve permitir que Usuário efetue cadastro.|
|RF02|O sistema deve permitir que o Usuário faça login.|
|RF03|O sistema deve permitir que o Usuário consulte os espaços.|
|RF04|O sistema deve permitir que o Usuário reserve espaços.|
|RF05|O sistema deve permitir que o Usuário exclua reserva.|
|RF06|O sistema deve permitir o Administrador tornar outro Usuário Administrador.|
|RF07|O sistema deve permitir que o Usuário pesquise espaços por disponibilidade.|
|RF08|O sistema deve permitir que o Usuário pesquise espaços por horário.|
|RF09|O sistema deve permitir que o Usuário pesquise espaços por nome do espaços.|
|RF10|O sistema deve enviar informações da reserva ao email cadastrado do Usuário.|
|RF11|O sistema deve permitir que o Usuário atualize seu cadastro.|
|RF12|O sistema deve permitir que o Usuário delete seu cadastro.|
|RF13|O sistema deve permitir que o Administrador delete o cadastro de qualquer Usuário.|
|RF14|O sistema deve mostrar um mapa de localização dos espaços.|
|RF15|O sistema deve gerar relatório de utilização de determinado espaço por período.|
|RF16|O sistema deve gerar relatório de utilização de espaços por Usuário.|
|RF17|O sistema deve permitir que o usuário liste suas reservas.|
|RF18|O sistema deve permitir que o usuário consulte suas reservas.|
|RF19|O sistema deve permitir que o usuário visualize a página de perguntas frequentes.|


##4. Casos de Uso

|ID|Caso de Uso|
|----|------|
|UC01|Manter usuário|
|UC02|Realizar login|
|UC03|Criar reserva|
|UC04|Consultar reserva|
|UC05|Excluir reserva|
|UC06|Consultar espaços|
|UC07|Gerenciar administradores|
|UC08|Aprovar reserva|
|UC09|Consultar Perguntas Frequentes|
|UC10|Gerar Relatório|


##5. Necessidades X Requisitos do Sistema

|      |RF01|RF02|RF03|RF04|RF05|RF06|RF07|RF08|RF09|RF10|RF11|RF12|RF13|RF14|RF15|RF16|RF17|RF18|RF19|
|------|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
|**N1**|x   |x   |x   |x   |x   |    |x   |x   |x   |    |    |    |    |    |    |    |x   |x   |x   |
|**N2**|x   |x   |x   |x   |x   |    |x   |x   |x   |    |    |    |    |    |    |    |x   |x   |x   |
|**N3**|x   |    |x   |x   |x   |    |x   |x   |x   |    |    |    |    |x   |x   |x   |x   |x   |    |
|**N4**|x   |x   |    |    |    |x   |    |    |    |x   |x   |x   |x   |    |    |x   |    |    |    |

##6. Requisitos do Sistema X Casos de uso

|        |UC01|UC02|UC03|UC04|UC05|UC06|UC07|UC08|UC09|UC10|
|--------|----|----|----|----|----|----|----|----|----|----|
|**RF01**| X  |    |    |    |    |    |    |    |    |    |
|**RF02**|    | X  |    |    |    |    |    |    |    |    |
|**RF03**|    |    | X  |    |    | X  |    |    |    |    |
|**RF04**|    |    | X  |    |    |    |    | X  |    |    |
|**RF05**|    |    |    |    | X  |    |    |    |    |    |
|**RF06**|    |    |    |    |    |    | X  |    |    |    |
|**RF07**|    |    |    |    |    | X  |    |    |    |    |
|**RF08**|    |    |    |    |    | X  |    |    |    |    |
|**RF09**|    |    |    |    |    | X  |    |    |    |    |
|**RF10**|    |    | X  |    |    |    |    |    |    |    |
|**RF11**| X  |    |    |    |    |    |    |    |    |    |
|**RF12**| X  |    |    |    |    |    |    |    |    |    |
|**RF13**| X  |    |    |    |    |    |    |    |    |    |
|**RF14**|    |    |    |    |    | X  |    |    |    |    |
|**RF15**|    |    |    |    |    |    |    |    |    | X  |
|**RF16**|    |    |    |    |    |    |    |    |    | X  |
|**RF17**|    |    |    | X  | X  |    |    |    |    |    |
|**RF18**|    |    |    | X  | X  |    |    |    |    |    |
|**RF18**|    |    |    |    |    |    |    |    | X  |    |


##7. Diagrama de Rastreabilidade