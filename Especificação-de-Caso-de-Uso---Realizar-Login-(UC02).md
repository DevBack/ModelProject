[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)

#1. Descrição
Permite que usuários cadastrados tenham acesso as demais funcionalidades do sistema que exijam autenticação.

#2. Ator

Corpo Acadêmico e Administrador.

#3. Pré condição
O usuário deve possuir cadastro no sistema.

#4. Pós condição

O usuário estará logado no sistema e terá acesso as demais funcionalidades.

#5. Fluxo Principal
[FP01] O caso de uso se inicia quando o usuário seleciona a opção de “Entrar” na página principal.

[FP02] O sistema encaminha o usuário para a página de login.

[FP03] O usuário preenche seus dados na página de  login.

[FP04] O usuário aperta no botão "Entrar" para enviar seus dados. 

[FP05] O sistema verifica os dados digitados.

[FP06] O sistema encaminha o usuário para sua página de perfil.



#6. Fluxo de Exceção

[FE01] No passo 5 do fluxo principal [FP05] o usuário preencheu uma matrícula que não existe, retorna para [FP03] sinalizando que o usuário digitado não existe.

[FE02] No passo 5 do fluxo principal [FP05] o usuário digitou a senha incorreta, retorna para [FP03] sinalizando que a senha digitada não confere.

[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)