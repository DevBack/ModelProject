[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)

#1. Descrição

Permite que usuários cadastrados consultem suas reservas de espaços.

#2. Ator

Corpo Acadêmico: consulta apenas suas próprias reservas de espaço.

Administrador: pode consultar qualquer reserva de espaço.

#3. Pré condição

O usuário deve estar logado.

#4. Pós condição

Visualização dos dados da reserva.

#5. Fluxo Principal

[FP01] O caso de uso se inicia quando o usuário seleciona a opção de “Minhas Reservas” na barra de menu.

[FP02] O sistema encaminha o usuário para a página de reservas e lista todas as suas reservas.

[FP03] O usuário aperta no botão "lupa", da reserva que deseja consultar, para enviar a solicitação.

[FP04] O sistema encaminha o usuário para a página com os dados da reserva.

[FP05] O usuário consulta os dados da sua reserva.

[FP06] O usuário clica no botão de "Voltar".

[FP07] O sistema encaminha o usuário para a página de reservas e lista todas as suas reservas.


#6. Fluxo de Alternativo

[FA01]  O administrador consulta uma reserva de outro usuário.

[FA01.1] O administrador clica na opção de pesquisar usuários.

[FA01.2] O administrador insere o nome do usuário que deseja pesquisar.

[FA01.3] O administrador seleciona o usuário que deseja ver.

[FA01.4] O administrador seleciona seleciona a opção "visualizar reservas".

[FA01.5] O administrador é encaminhado para o [FP02] do "Consultar Reserva".


[FA02] Após o passo 2 do fluxo principal [FP02] o usuário queira encontrar a reserva que deseja excluir por nome da reserva e/ou data da reserva, ele preenche ao menos um desses campos, retorna para [FP03]

#7. Fluxo de Exceção

[FE01] No passo 2 do [FA01] o administrador digita o nome de um usuário que não existe, retorna para [FA01] sinalizando que o usuário digitado não existe.

[FE02] No [FA02] o usuário digita o nome de uma reserva e/ou a data de uma reserva que ele não possui, retorna para [FP02] sinalizando que não existe reserva com esse nome e/ou data.

[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)