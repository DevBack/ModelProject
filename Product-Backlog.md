## 1. Introdução
O presente documento apresenta todas as histórias técnicas e de usuário a serem realizadas durante a _Release 2_ do projeto SAS (Sistema de Alocação de Salas). Tais histórias foram pontuadas de acordo com seu nível de complexidade, resultando em um total planejado de **148 pontos**.

## 2. Histórias de usuário

|US (User Story) | História | Pontuação |
|----------------|----------|-----------|
| #1 | Como um administrador, quero consultar os dados de todos os usuários cadastrados no sistema. | 13 | 
| #2 | Como um administrador, quero consultar todas reservas já efetuadas visualizando todos dados. | 8 |
| #3 | Como um usuário, quero excluir as reservas feitas por mim. | 5 | 
| #4 | Como administrador, quero excluir qualquer reserva efetuada. | 8 |
| #5 | Como um visitante, quero consultar a disponibilidade e as reservas já realizadas em determinado espaço. | 13 |
| #6 | Como um administrador, quero gerenciar administradores do sistema de modo que consiga tornar um usuário do corpo acadêmico em administrador. | 13 |
| #7 | Como um administrador, quero aprovar reservas de laboratórios solicitadas pelo corpo acadêmico. | 13 |
| #8 | Como um visitante, quero consultar as perguntas frequentes do sistema. | 3 |
| #9 | Como um administrador, quero visualizar relatórios de reserva de modo que possa identificar os espaços mais utilizados em determinados períodos. | 20 |

## 3. Histórias técnicas (de teste e refatoração)

|TS (Techinical Story) | História | Pontuação |
|----------------|----------|-----------|
| #1 | Como um desenvolvedor, eu quero criar um app de usuário para melhorar a gerência dos usuários. | 3  |
| #2 | Como um desenvolvedor, eu quero realizar as validações necessárias do cadastro de usuário para garantir a consistência dos dados inseridos. | 5  |
| #3 | Como um desenvolvedor, eu quero testar o cadastro de usuário para garantir a funcionalidade do método.| 3 |
| #4 | Como um desenvolvedor, eu quero realizar as validações necessárias da alteração de usuário para garantir a consistência dos dados inseridos. | 3 |
| #5 | Como um desenvolvedor, eu quero testar a alteração de usuário para garantir a funcionalidade do método. | 3 |
| #6 | Como um desenvolvedor, eu quero testar a exclusão de usuário para garantir a funcionalidade do método. | 2 |
| #7 | Como um desenvolvedor, eu quero testar a consulta de usuário para garantir a funcionalidade do método. | 2 |
| #8 | Como um desenvolvedor, eu quero realizar as validações necessárias do login de usuário para garantir a consistência dos dados inseridos. | 2 |
| #9 | Como um desenvolvedor, eu quero testar o login e logout de usuário para garantir a funcionalidade do método. | 3 |
| #10 | Como um desenvolvedor, eu quero realizar as validações necessárias da criação de reserva para garantir a consistência dos dados inseridos. | 8 |
| #11 | Como um desenvolvedor, eu quero testar a criação de reserva para garantir a funcionalidade do método. | 5 | 
| #12 | Como um desenvolvedor, eu quero refatorar o cadastro de criação de reserva para consertar os bugs conhecidos. | 8 |
| #13 | Como um desenvolvedor, eu quero testar a consulta de reserva para garantir a funcionalidade do método. | 5 |