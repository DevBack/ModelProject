[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)

# **Índice**


[1. Cadastrar Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Uso---Manter-Usu%C3%A1rio-(UC01)#1-cadastrar-usu%C3%A1rio)

[2. Alterar Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Uso---Manter-Usu%C3%A1rio-(UC01)#2-alterar-usu%C3%A1rio)

[3. Excluir Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Uso---Manter-Usu%C3%A1rio-(UC01)#3-excluir-usu%C3%A1rio)

[4. Ver Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Uso---Manter-Usu%C3%A1rio-(UC01)#4-ver-usu%C3%A1rio)

#1. Cadastrar Usuário

##1.1. Descrição
Permite que sejam criados novos usuários no sistema.

##1.2. Ator

Corpo Acadêmico.

##1.3. Pré condição
Nenhuma

##1.4. Pós condição

Cadastro do usuário no sistema.

##1.5. Regras de Negócio
RN08 Formato dos dados de cadastro de usuário.

|Nome|Formato|
|----|------|
|Nome|No mínimo 2 no máximo 50 caracteres.|
|Email|Deve possuir formato válido como no exemplo: email@exemplo.com.|
|Matrícula|Deve possuir apenas números.|
|Senha|No mínimo 6 caracteres, no máximo 15.|
|Confirmação de senha|Deve estar preenchido de forma idêntica a senha.|


##1.6. Fluxo Principal



[FP01] O caso de uso se inicia quando o usuário seleciona a opção cadastrar.

[FP02] O usuário preenche os dados, seguindo a RN08.

[FP03] O usuário aperta no botão "confirmar" para enviar seus dados.

[FP04] O sistema verifica os dados digitados.

[FP05] O sistema guarda os dados do usuário.

[FP06] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de cadastro.

##1.7. Fluxo de Exceção


[FE01] No passo 2 do fluxo principal [FP02] o usuário não preencheu os dados corretamente, retorna para [FP02] sinalizando qual campo não foi preenchido de forma correta.

[FE01] No passo 2 do fluxo principal [FP02] o usuário preencheu a matrícula de alguém que já está cadastrado, retorna para [FP02], sinalizando que já existe esse cadastro.




#2. Alterar Usuário

##2.1. Descrição
Permite que sejam alterados cadastros de usuários no sistema.


##2.2. Atores

Corpo Acadêmico (Principal): altera apenas o seu próprio cadastro.

Administrador: altera seu cadastro e de qualquer outro usuário.


##2.3. Pré condição
O Usuário deve ter acessado o sistema e estar logado.

##2.4. Pós condição

Alteração dos dados do usuário no sistema.

##2.5. Regras de Negócio
RN09 Para alterar a senha o usuário deve digitar a senha atual.


##2.6. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02] O sistema redireciona o usuário para a página de perfil.

[FP03] O usuário altera os dados, respeitando a RN08(Apenas email, nome e senha).

[FP04] O usuário confirma a alteração.

[FP05] O sistema verifica os dados digitados.

[FP06] O sistema salva os dados alterados.

[FP07] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de alteração.

##2.7. Fluxo Alternativo
[FA01] O administrador altera o cadastro de um outro usuário. Este fluxo inicia-se no passo [FP01]

[FA01.1] O administrador clica na opção de pesquisar usuários.

[FA01.2] O administrador insere o nome do usuário que deseja pesquisar.

[FA01.3] O administrador seleciona o usuário que deseja editar.

[FA01.4] O administrador clica em “editar usuário”.

[FA01.5] O administrador é encaminhado para o [FP02] do “Alterar Usuário”.

##2.8. Fluxo de Exceção


[FE01] No passo 3 do fluxo principal [FP03] o usuário não preencheu os dados corretamente, retorna para [FP03] sinalizando qual campo não foi preenchido de forma correta.
[FE01] No fluxo alternativo [FA01] o administrador pesquisa o nome de um usuário que não existe, retorna para [FA01] sinalizando que não foi encontrado o usuário.




#3. Excluir Usuário

##3.1. Descrição
Permite que sejam excluídos cadastros de usuários do sistema.


##3.2. Atores

Corpo acadêmico: exclui apenas seu próprio cadastro.

Administrador(Principal): pode excluir o cadastro de qualquer outro usuário, mas não o seu.


##3.3. Pré condição
O usuário deve ter acessado e estar logado.

##3.4. Pós condição

Exclusão do cadastro do usuário do sistema.

##3.5. Regras de Negócio
RN10 Para excluir a conta o usuário deve clicar no botão “Confirmar” na caixa de diálogo de confirmação de exclusão que aparecerá.

##3.6. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02] O usuário é encaminhado para a página de perfil.

[FP03] O usuário clica na opção “Excluir Cadastro”.

[FP04] O usuário confirma a opção de excluir cadastro, conforme a RN03.

[FP05] O sistema exclui os dados do usuário.

[FP06] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de exclusão.

##3.7. Fluxo Alternativo
[FA01] O administrador exclui o cadastro de um outro usuário. Este fluxo inicia-se no passo [FP01]

[FA01.1] O administrador clica na opção de pesquisar usuários.

[FA01.2] O administrador insere o nome do usuário que deseja pesquisar.

[FA01.3] O administrador seleciona o usuário que deseja excluir.

[FA01.4] O administrador clica em “Excluir Usuário”.

[FA01.5] O administrador é encaminhado para o [FP02] do “Excluir Usuário”.


##3.8. Fluxo de Exceção

[FE01] No passo 4 do fluxo principal [FP04] o usuário clicou em “Cancelar” na caixa de diálogo de confirmação para excluir conta, retorna para [FP02].

[FE02] No fluxo alternativo 1 [FA01] o administrador pesquisa o nome de um usuário que não existe, retorna para [FA01] sinalizando que não foi encontrado o usuário.


#4. Ver Usuário

##1.4.1. Descrição
Permite que sejam visualizados os dados de cadastro de usuários do sistema.


##4.2. Atores

Corpo acadêmico (Principal) : visualiza apenas seus dados cadastrais.

Administrador: pode visualizar seus dados cadastrais ou de qualquer outro usuário.


##4.3. Pré condição
O usuário deve ter acessado e estar logado.

##4.4. Pós condição

Visualização dos dados cadastrais do usuário do sistema.

##4.5. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02] O usuário é encaminhado para a página de perfil.

[FP03] O usuário visualiza seus dados cadastrais.

[FP04] O usuário clica na opção de voltar à página inicial.

[FP05] O sistema encaminha o usuário para página inicial.

##4.6. Fluxo Alternativo
[FA01]No passo [FP01] o administrador deseja consultar o perfil de outro usuário.

[FA01.1] O administrador clica na opção de pesquisar usuários.

[FA01.2] O administrador insere o nome do usuário que deseja pesquisar.

[FA01.3] O administrador seleciona o usuário que deseja ver.

[FA01.4] O administrador é encaminhado para o [FP02] do “Ver Usuário”.

##4.7. Fluxo de Exceção

[FE01] No fluxo alternativo [FA01] o administrador pesquisa o nome de um usuário que não existe, retorna para [FA01] sinalizando que não foi encontrado o usuário.


[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)