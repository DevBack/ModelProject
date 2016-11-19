## 1. Introdução
O presente documento apresenta todas as histórias técnicas e de usuário a serem realizadas durante a _Release 2_ do projeto SAS (Sistema de Alocação de Salas). Tais histórias foram pontuadas de acordo com seu nível de complexidade, resultando em um total planejado de **239 pontos**.

## 2. Histórias de usuário

|Issue|US (User Story) | História | Pontuação Inicial |Pontuação Replanejada|Pontuação Nova|
|-----|----------------|----------|-----------|--------------|
|[#17](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/17) | #1 | Como um administrador, quero consultar os dados de todos os usuários cadastrados no sistema para poder identificar um usuário. | 13 | 8|---|
|[#18](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/18)  | #2 | Como um administrador, quero consultar todas reservas já efetuadas visualizando todos dados para administrar as reservas. | 8 |---|---|
|[#20](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/20) | #3 | Como um usuário, quero excluir as reservas feitas por mim para disponibilizar espaços dos quais não preciso mais. | 5 | ---|---|
|[#21](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/21) | #4 | Como administrador, quero excluir qualquer reserva efetuada para liberar espaços necessários a eventos de maior prioridade. | 8 |---|---|
|[#22](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/22) | #5 | Como um usuário, quero consultar a disponibilidade e as reservas já realizadas em determinado espaço para ter um mecanismo de busca mais objetivo. | 13 |20|---|
| [#23](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/23) | #6 | Como um administrador, quero gerenciar administradores do sistema de modo que consiga tornar um usuário do corpo acadêmico em administrador para conseguir dividir a função de administrador com outros usuários. | 13 | 8|---|
|[#24](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/24)  | #7 | Como um administrador, quero aprovar reservas de laboratórios solicitadas pelo corpo acadêmico para ter um maior controle sobre quem utiliza os laboratórios. | 13 |8|---|
|[#25](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/25) | #8 | Como um visitante, quero consultar as perguntas frequentes do sistema para sanar dúvidas sobre o sistema. | 3 |1|---|
|[#26](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/26) | #9 | Como um administrador, quero visualizar relatórios de reserva para que possa identificar os espaços mais utilizados em determinados períodos. | 20 |---|---|
|[#83](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/83)|#10| Como usuário, eu quero reservar um espaço a partir da tabela de ocupação para utilizar a sala.|---|---|8|
|[#84](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/84)|#11| Como administrador, eu quero designar um responsável pelas reservas que eu cadastrar para manter o controle da reserva. |---|---|13|
|[#89](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/89)|#12| Como usuário, eu quero selecionar qual a Engenharia que curso durante o meu cadastro, para o administrador ter um controle de reservas por Engenharia.|---|---|3|
|[#90](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/90)|#13| Como administrador, quero selecionar uma engenharia ao criar uma reserva, para ter o controle por curso.|---|---|2|
|[#91](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/91)|#14| Como administrador, quero poder pesquisar uma reserva pelo nome do responsável, para conseguir localizar em qual sala está um professor.|---|---|2|
|[#92](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/92)|#15|Como administrador, quero cadastrar datas de início e fim para um semestre e ao criar uma reserva selecionar o semestre ao invés das datas, para agilizar o processo de criar reserva.|---|---|3|
|[#93](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/93)|#16| Como administrador, quero excluir apenas um horário específico da reserva, para aproveitar melhor os espaços da FGA.|---|---|2|
|[#94](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/94)|#17| Como administrador, quero visualizar a capacidade de cada sala ao fazer a reserva, para conseguir alocar as disciplinas melhor.|---|---|2|
|[#110] (https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/110)|#18| Como administrador, quero cadastrar tags (#) para depois conseguir gerar um relatório de acordo com as tags selecionadas.|---|---|20|
| | | **TOTAL** | **151** | 

## 3. Histórias técnicas (teste e refatoração)

|Issue|TS (Techinical Story) | História | Pontuação |Nova Pontuação|
|-----|----------------------|----------|-----------|--------------|
|[#3](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/3)  | #1 | Como um desenvolvedor, eu quero criar um app de usuário para melhorar a gerência dos usuários. | 3  |---|---|
|[#4](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/4)  | #2 | Como um desenvolvedor, eu quero realizar as validações necessárias do cadastro de usuário para garantir a consistência dos dados inseridos. | 5  |---|---|
|[#5](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/5) | #3 | Como um desenvolvedor, eu quero testar o cadastro de usuário para garantir a funcionalidade do método.| 3 |---|---|
|[#6](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/6) | #4 | Como um desenvolvedor, eu quero realizar as validações necessárias da alteração de usuário para garantir a consistência dos dados inseridos. | 3 |---|---|
|[#7](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/7) | #5 | Como um desenvolvedor, eu quero testar a alteração de usuário para garantir a funcionalidade do método. | 3 |---|---|
|[#8](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/8) | #6 | Como um desenvolvedor, eu quero testar a exclusão de usuário para garantir a funcionalidade do método. | 2 |---|---|
|[#9](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/9) | #7 | Como um desenvolvedor, eu quero testar a consulta de usuário para garantir a funcionalidade do método. | 2 |---|---|
|[#10](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/10) | #8 | Como um desenvolvedor, eu quero realizar as validações necessárias do login de usuário para garantir a consistência dos dados inseridos. | 2 |---|---|
|[#11](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/11) | #9 | Como um desenvolvedor, eu quero testar o login e logout de usuário para garantir a funcionalidade do método. | 3 |---|---|
|[#12](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/12) | #10 | Como um desenvolvedor, eu quero realizar as validações necessárias da criação de reserva para garantir a consistência dos dados inseridos. | 8 |5|---|
|[#13](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/13) | #11 | _Como um desenvolvedor, eu quero testar a criação de reserva para garantir a funcionalidade do método._ | 5 | ---|---|
|[#14](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/14) | #12 | Como um desenvolvedor, eu quero refatorar o cadastro de criação de reserva para consertar os bugs conhecidos. | 8 |---|---|
|[#16](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/16) | #13 | _Como um desenvolvedor, eu quero testar a consulta de reserva para garantir a funcionalidade do método._ | 5 |---|---|
|[#62] (https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/62) | #14 | Como um desenvolvedor, eu quero internacionalizar o SAS para inglês. | ---|---|1|
|[#63] (https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/63) | #15 | Como um desenvolvedor, eu quero refatorar as views, para melhorar a qualidade do código. | ---|---|13|
|[#74] (https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/74) | #16 | Como desenvolvedor, eu quero refatorar a criação de reservas, para ficar mais intuitivo.| ---|---|8|
|[#85](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/85)|#17 | Como desenvolvedor, eu quero fazer deploy para colocar o SAS em produção. |---|---|2|
|[#96](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/96)|#18| Como desenvolvedor, eu quero melhorar as colunas das datatables, incluindo dia da semana e horário, para entender melhor as reservas.|---|---|5|
|[#97](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/97)|#19|Como desenvolvedor, eu quero mostrar a tabela das consultas mesmo sem existir nenhuma reserva nos filtros selecionados, para possibilitar a inclusão de uma reserva.|---|---|2|
|[#98](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/issues/98)|#20|Como desenvolvedor, quero facilitar a criação de reserva possibilitando selecionar sala sem ser obrigatório a seleção de prédio.|---|---|5|
| | | **TOTAL** | **88** | 


## 4. Critérios de Aceitação

###US #1 - Como um administrador, quero consultar os dados de todos os usuários cadastrados no sistema para poder identificar um usuário.

 * O sistema deve exibir todos usuários do sistema.
 * Apenas os administradores podem ter acesso a essa função.
 * O administrador pode ver todos os campos: nome, matrícula, categoria e tipo de cada usuário
 * O administrador pode visualizar dados de qualquer usuário, inclusive de outros administradores.


###US #2 - Como um administrador, quero consultar todas reservas já efetuadas visualizando todos dados para administrar as reservas. 
 * O sistema deve listar as reservas de todos os usuários, inclusive de administradores.
 * O sistema deve oferecer filtros para facilitar a busca de uma reserva.
 * Apenas os administradores podem ter acesso a essa função.


### US #3 - Como um usuário, quero excluir as reservas feitas por mim para disponibilizar espaços dos quais não preciso mais.
 * O usuário pode excluir apenas reservas feitas por ele.
 * O sistema deve exibir uma mensagem de confirmação para o usuário excluir a reserva.
 * O sistema ao excluir a reserva deve informar que esta foi excluída com sucesso.
 * O sistema, ao excluir a reserva, deve apagá-la do banco de dados.

### US #4 - Como administrador, quero excluir qualquer reserva efetuada para liberar espaços necessários a eventos de maior prioridade.  
 * O administrador pode excluir qualquer reserva, feitas por ele ou por outro usuário..
 * O sistema deve exibir uma mensagem de confirmação para o administrador excluir a reserva.
 * O sistema ao excluir a reserva deve informar que esta foi excluída com sucesso.
 * O sistema, ao excluir a reserva, deve apagá-la do banco de dados.  

### US #5 - Como um usuário, quero consultar a disponibilidade e as reservas já realizadas em determinado espaço para ter um mecanismo de busca mais objetivo.

 *	O sistema deve oferecer filtros necessário para pesquisa.
 *	O sistema deve ser claro na impressão da busca para o usuário.
 *	O sistema deve exibir quais são os espaços disponíveis baseado no filtro.
 *	O sistema deve exibir os resultados de forma visualmente agradável e intuitiva.


### US #6 - Como um administrador, quero gerenciar administradores do sistema de modo que consiga tornar um usuário do corpo acadêmico em administrador para conseguir dividir a função de administrador com outros usuários.

 *	O administrador pode tornar qualquer outro usuário administrador. 
 *	O sistema deve exibir todos usuários do sistema.
 *	O sistema deve informar que o usuário selecionado agora é administrador.
 *	Apenas os administradores podem ter acesso a essa função.

### US #7 - Como um administrador, quero aprovar reservas de laboratórios solicitadas pelo corpo acadêmico para ter um maior controle sobre quem utiliza os laboratórios.

 *      O administrador pode aprovar uma reserva de laboratório.
 *      O administrador pode recusar uma reserva de laboratório.
 *      O administrador pode ver todas as solicitações de reserva de laboratório.
 *      O administrador pode ver dados de quem solicitou a reserva do laboratório. 

### US #8 - Como um visitante, quero consultar as perguntas frequentes do sistema para sanar dúvidas sobre o sistema.

 *      O visitante pode ver a página de perguntas frequentes.
 *      A página de perguntas frequentes deve conter, no mínimo, dez perguntas frequentes.
 *      A página de perguntas frequentes deve ser agradável visualmente.
 *      Os tópicos abordados na página de perguntas frequentes devem ser autoexplicativos.

### US #9 - Como um administrador, quero visualizar relatórios de reserva para que possa identificar os espaços mais utilizados em determinados períodos.

 *	Apenas administradores podem gerar relatórios. 
 *	O sistema deve exibir informações sobre ocupações de espaços em um documento pdf.
 *	O sistema deve exibir essas informações de forma intuitiva.