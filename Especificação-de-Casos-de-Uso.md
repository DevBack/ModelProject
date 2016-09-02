# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|01/09/2016 |1.0 |Criando Cadastrar Usuário e Alterar Usuário |Fabíola |

#1. Manter Usuário - UC01

##1.1. Cadastrar Usuário

###1.1.1. Descrição
Permite que sejam criados novos usuários no sistema.

###1.1.2. Ator

Corpo Acadêmico.

###1.1.3. Pré condição
O usuário deve ter acessado o sistema.

###1.1.4. Pós condição

Cadastro do usuário no sistema.

###1.1.5. Regras de Negócio
RN08 Formato dos dados de cadastro de usuário.

|Nome|Formato|
|----|------|
|Nome|No mínimo 15 no máximo 50 caracteres.|
|Email|Deve possuir formato válido como no exemplo: email@exemplo.com.|
|Matrícula|Deve possuir apenas números.|
|Senha|No mínimo 6 caracteres, no máximo 15.|
|Confirmação de senha|Deve estar preenchido de forma idêntica a senha.|


###1.1.6. Fluxo Principal

[FP01] O usuário acessa o sistema.

[FP02] O usuário entra na página de cadastro.

[FP03] O usuário preenche os dados, seguindo a RN01.

[FP04] O usuário confirma o cadastro.

[FP05] O sistema valida os dados digitados.

[FP06] O sistema persiste os dados no banco.

[FP07] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de cadastro.

###1.1.7. Fluxo de Exceção

[FE01]O usuário não preencheu os dados corretamente, retorna para [FP02] sinalizando qual campo não foi preenchido de forma correta.

[FE01]Já existe cadastro com aquela matrícula, retorna para [FP02], sinalizando que já existe esse cadastro.




##1.2. Alterar Usuário

###1.2.1. Descrição
Permite que sejam alterados cadastros de usuários no sistema.


###1.2.2. Atores

Corpo Acadêmico: altera apenas o seu próprio cadastro.
Administrador: altera seu cadastro e de qualquer outro usuário.


###1.2.3. Pré condição
O Usuário deve ter acessado o sistema e estar logado.

###1.2.4. Pós condição

Alteração dos dados do usuário no sistema.

###1.2.5. Regras de Negócio
RN09 Para alterar a senha o usuário deve digitar a senha atual.


###1.2.6. Fluxo Principal

[FP01] O usuário clica em “Perfil”.

[FP02]O usuário é encaminhado para a página de perfil.

[FP03] O usuário altera os dados, respeitando a RN01.

[FP04] O usuário confirma a alteração.

[FP05] O sistema valida os dados digitados.

[FP06] O sistema persiste os dados no banco.

[FP07] O sistema encaminha o usuário para página inicial e retorna mensagem de sucesso de alteração.

###1.2.7. Fluxo Alternativo
Para o administrador alterar o cadastro de um outro usuário.

[FA01] O administrador pesquisa um usuário.

[FA02] O administrador seleciona um usuário.

[FA03] O administrador clica em “editar usuário”.

[FA04] O administrador é encaminhado para o [FP02] do “Alterar Usuário”.

###1.2.8. Fluxo de Exceção

O usuário não preencheu os dados corretamente, retorna para [FP02] sinalizando qual campo não foi preenchido de forma correta.