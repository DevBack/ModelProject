# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|01/09/2016 |1.0 |Criando Cadastrar Usuário e Alterar Usuário |Fabíola |
|02/09/2016 |1.1 |Criando Excluir Usuário e Ver Usuário |Luis |
|04/09/2016 |1.2 |Revisão do UC01 |Fabíola |
|08/09/2016 |1.3 |Revisão do UC01 |Luis |
|08/09/2016 |1.4 |Adicionando o UC02|Fabíola |
|08/09/2016 |1.5 |Adicionando o UC03|Fabíola |
|08/09/2016 |1.6 |Adicionando o UC04|Fabíola |
|12/09/2016 |1.7 |Revisão dos UC02, UC03 e UC04|Fabíola |
|13/09/2016 |1.8 |Revisão dos UC02, UC03 e UC04|Luis |

#1. Manter Usuário - UC01

##1.1. Cadastrar Usuário

###1.1.1. Descrição
Permite que sejam criados novos usuários no sistema.

###1.1.2. Ator

Corpo Acadêmico.

###1.1.3. Pré condição
Nenhuma

###1.1.4. Pós condição

Cadastro do usuário no sistema.

###1.1.5. Regras de Negócio
RN08 Formato dos dados de cadastro de usuário.

|Nome|Formato|
|----|------|
|Nome|No mínimo 2 no máximo 50 caracteres.|
|Email|Deve possuir formato válido como no exemplo: email@exemplo.com.|
|Matrícula|Deve possuir apenas números.|
|Senha|No mínimo 6 caracteres, no máximo 15.|
|Confirmação de senha|Deve estar preenchido de forma idêntica a senha.|


###1.1.6. Fluxo Principal



[FP01] O caso de uso se inicia quando o usuário seleciona a opção cadastrar.

[FP02] O usuário preenche os dados, seguindo a RN08.

[FP03] O usuário aperta no botão "confirmar" para enviar seus dados.

[FP04] O sistema verifica os dados digitados.

[FP05] O sistema guarda os dados do usuário.

[FP06] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de cadastro.

###1.1.7. Fluxo de Exceção


[FE01] No passo 2 do fluxo principal [FP02] o usuário não preencheu os dados corretamente, retorna para [FP02] sinalizando qual campo não foi preenchido de forma correta.

[FE01] No passo 2 do fluxo principal [FP02] o usuário preencheu a matrícula de alguém que já está cadastrado, retorna para [FP02], sinalizando que já existe esse cadastro.




##1.2. Alterar Usuário

###1.2.1. Descrição
Permite que sejam alterados cadastros de usuários no sistema.


###1.2.2. Atores

Corpo Acadêmico (Principal): altera apenas o seu próprio cadastro.

Administrador: altera seu cadastro e de qualquer outro usuário.


###1.2.3. Pré condição
O Usuário deve ter acessado o sistema e estar logado.

###1.2.4. Pós condição

Alteração dos dados do usuário no sistema.

###1.2.5. Regras de Negócio
RN09 Para alterar a senha o usuário deve digitar a senha atual.


###1.2.6. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02] O sistema redireciona o usuário para a página de perfil.

[FP03] O usuário altera os dados, respeitando a RN08(Apenas email, nome e senha).

[FP04] O usuário confirma a alteração.

[FP05] O sistema verifica os dados digitados.

[FP06] O sistema salva os dados alterados.

[FP07] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de alteração.

###1.2.7. Fluxo Alternativo
[FA01] O administrador altera o cadastro de um outro usuário. Este fluxo inicia-se no passo [FP01]

* O administrador clica na opção de pesquisar usuários.

* O administrador insere o nome do usuário que deseja pesquisar.

* O administrador seleciona o usuário que deseja editar.

* O administrador clica em “editar usuário”.

* O administrador é encaminhado para o [FP02] do “Alterar Usuário”.

###1.2.8. Fluxo de Exceção


[FE01] No passo 3 do fluxo principal [FP03] o usuário não preencheu os dados corretamente, retorna para [FP03] sinalizando qual campo não foi preenchido de forma correta.
[FE01] No fluxo alternativo [FA01] o administrador pesquisa o nome de um usuário que não existe, retorna para [FA01] sinalizando que não foi encontrado o usuário.




##1.3. Excluir Usuário

###1.3.1. Descrição
Permite que sejam excluídos cadastros de usuários do sistema.


###1.3.2. Atores

Corpo acadêmico: exclui apenas seu próprio cadastro.

Administrador(Principal): pode excluir o cadastro de qualquer outro usuário, mas não o seu.


###1.3.3. Pré condição
O usuário deve ter acessado e estar logado.

###1.3.4. Pós condição

Exclusão do cadastro do usuário do sistema.

###1.3.5. Regras de Negócio
RN10 Para excluir a conta o usuário deve clicar no botão “Confirmar” na caixa de diálogo de confirmação de exclusão que aparecerá.

###1.3.6. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02] O usuário é encaminhado para a página de perfil.

[FP03] O usuário clica na opção “Excluir Cadastro”.

[FP04] O usuário confirma a opção de excluir cadastro, conforme a RN03.

[FP05] O sistema exclui os dados do usuário.

[FP06] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de exclusão.

###1.3.7. Fluxo Alternativo
[FA01] O administrador exclui o cadastro de um outro usuário. Este fluxo inicia-se no passo [FP01]

* O administrador clica na opção de pesquisar usuários.

* O administrador insere o nome do usuário que deseja pesquisar.

* O administrador seleciona o usuário que deseja excluir.

* O administrador clica em “Excluir Usuário”.

* O administrador é encaminhado para o [FP02] do “Excluir Usuário”.


###1.3.8. Fluxo de Exceção

[FE01] No passo 4 do fluxo principal [FP04] o usuário clicou em “Cancelar” na caixa de diálogo de confirmação para excluir conta, retorna para [FP02].

[FE02] No fluxo alternativo 1 [FA01] o administrador pesquisa o nome de um usuário que não existe, retorna para [FA01] sinalizando que não foi encontrado o usuário.


##1.4. Ver Usuário

###1.4.1. Descrição
Permite que sejam visualizados os dados de cadastro de usuários do sistema.


###1.4.2. Atores

Corpo acadêmico (Principal) : visualiza apenas seus dados cadastrais.

Administrador: pode visualizar seus dados cadastrais ou de qualquer outro usuário.


###1.4.3. Pré condição
O usuário deve ter acessado e estar logado.

###1.4.4. Pós condição

Visualização dos dados cadastrais do usuário do sistema.

###1.4.5. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02] O usuário é encaminhado para a página de perfil.

[FP03] O usuário visualiza seus dados cadastrais.

[FP04] O usuário clica na opção de voltar à página inicial.

[FP05] O sistema encaminha o usuário para página inicial.

###1.4.6. Fluxo Alternativo
[FA01]No passo [FP01] o administrador deseja consultar o perfil de outro usuário.

* O administrador clica na opção de pesquisar usuários.

* O administrador insere o nome do usuário que deseja pesquisar.

* O administrador seleciona o usuário que deseja ver.

* O administrador é encaminhado para o [FP02] do “Ver Usuário”.

###1.4.7. Fluxo de Exceção

[FE01] No fluxo alternativo [FA01] o administrador pesquisa o nome de um usuário que não existe, retorna para [FA01] sinalizando que não foi encontrado o usuário.



#2. Realizar Login - UC02

##2.1. Descrição
Permite que usuários cadastrados tenham acesso as demais funcionalidades do sistema que exijam autenticação.

##2.2. Ator

Corpo Acadêmico e Administrador.

##2.3. Pré condição
O usuário deve possuir cadastro no sistema.

##2.4. Pós condição

O usuário estará logado no sistema e terá acesso as demais funcionalidades.

##2.5. Fluxo Principal
[FP01] O caso de uso se inicia quando o usuário seleciona a opção de “Entrar” na página principal.

[FP02] O sistema encaminha o usuário para a página de login.

[FP03] O usuário preenche seus dados na página de  login.

[FP04] O usuário aperta no botão "Entrar" para enviar seus dados. 

[FP05] O sistema verifica os dados digitados.

[FP06] O sistema encaminha o usuário para sua página de perfil.



##2.6. Fluxo de Exceção

[FE01] No passo 5 do fluxo principal [FP05] o usuário preencheu uma matrícula que não existe, retorna para [FP03] sinalizando que o usuário digitado não existe.

[FE02] No passo 5 do fluxo principal [FP05] o usuário digitou a senha incorreta, retorna para [FP03] sinalizando que a senha digitada não confere.


#3. Criar Reserva - UC03

##3.1. Descrição

Permite que usuários cadastrados efetuem a reserva de um espaço ou a requisição de reserva.

##3.2. Ator

Corpo Acadêmico: Efetua reservas no nome de sua conta

Administrador: pode efetuar reservas em nome de outro usuário.

##3.3. Pré condição

O usuário deve estar logado e deve ter consultado os espaços.

##3.4. Pós condição

O espaço será reservado ou uma reserva será requisitada para ele.

##3.5. Fluxo Principal

[FP01] O caso de uso se inicia após o usuário ter consultado os espaços.

[FP02] O usuário atribui um nome a sua reserva.

[FP03] O usuário aperta no botão "Efetuar reserva".

[FP04] O usuário aperta no botão "confirmar" para enviar a solicitação.

[FP05] O sistema efetua a reserva, exibindo uma mensagem de sucesso ao usuário.

##3.6. Fluxo Alternativo

[FA01] No passo [FP04], caso o espaço selecionado seja um laboratório, o sistema não efetuará a reserva mas sim deixará ela pendente para avaliação de um Administrador que poderá confirmá-la ou cancelar.

[FA02] O administrador reserva um espaço para outro usuário. Este fluxo inicia-se no passo [FP01]

* O administrador atribui um nome a sua reserva.

* O administrador aperta no botão "Efetuar reserva".

* O administrador seleciona marca a opção "reservar espaço para outro usuário".

* O administrador digita o nome do usuário ao qual deseja atribuir a reserva.

* O administrador seleciona o usuário que ao qual deseja atribuir a reserva.

* O administrador é encaminhado ao [FP03] do "Criar Reserva".

##3.7. Fluxo de Exceção

[FE01] No passo 4 do fluxo principal [FP04] o usuário aperta no botão "cancelar" , retorna para [FP01].

[FE02] No passo 4 do [FA02] o administrador digita o nome de um usuário que não existe, retorna para [FA02] sinalizando que o usuário digitado não existe.

#4. Excluir Reserva - UC04

##4.1. Descrição

Permite que usuários cadastrados excluam reservas de espaços.

##4.2. Ator

Corpo Acadêmico:exclui reservas feitas em seu nome.

Administrador: pode excluir qualquer reserva.

##4.3. Pré condição

O usuário deve estar logado.

##4.4. Pós condição

A reserva será excluída.

##4.5. Fluxo Principal

[FP01] O caso de uso se inicia quando o usuário seleciona a opção de “Minhas Reservas” na barra de menu.

[FP02] O sistema encaminha o usuário para a página de reservas.

[FP03] O usuário aperta no botão "x" para deletar para enviar a solicitação. 

[FP04] O usuário clica em "Confirmar".

[FP05] O sistema exclui a reserva e exibe uma mensagem para o usuário.


##4.6. Fluxo de Alternativo

[FA01] O administrador exclui uma reserva de outro usuário.

* O administrador clica na opção de pesquisar usuários.

* O administrador insere o nome do usuário que deseja pesquisar.

* O administrador seleciona o usuário que deseja ver.

* O administrador seleciona seleciona a opção "visualizar reservas"

* O administrador é encaminhado para o [FP02] do "Excluir Reserva".


##3.7. Fluxo de Exceção

[FE01] No passo 4 do fluxo principal [FP04] o usuário aperta no botão "cancelar" , retorna para [FP02].

[FE02] No passo 2 do [FA01] o administrador digita o nome de um usuário que não existe, retorna para [FA01] sinalizando que o usuário digitado não existe.
