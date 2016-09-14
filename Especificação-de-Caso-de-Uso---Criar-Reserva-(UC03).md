[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)

#1. Descrição

Permite que usuários cadastrados efetuem a reserva de um espaço ou a requisição de reserva.

#2. Ator

Corpo Acadêmico: Efetua reservas no nome de sua conta

Administrador: pode efetuar reservas em nome de outro usuário.

#3. Pré condição

O usuário deve estar logado e deve ter consultado os espaços.

#4. Pós condição

O espaço será reservado ou uma reserva será requisitada para ele.

#5. Fluxo Principal

[FP01] O caso de uso se inicia após o usuário ter consultado os espaços.

[FP02] O usuário atribui um nome a sua reserva.

[FP03] O usuário aperta no botão "Efetuar reserva".

[FP04] O usuário aperta no botão "confirmar" para enviar a solicitação.

[FP05] O sistema efetua a reserva, exibindo uma mensagem de sucesso ao usuário.

#6. Fluxo Alternativo

[FA01] No passo [FP04], caso o espaço selecionado seja um laboratório, o sistema não efetuará a reserva mas sim deixará ela pendente para avaliação de um Administrador que poderá confirmá-la ou cancelar.

[FA02] O administrador reserva um espaço para outro usuário. Este fluxo inicia-se no passo [FP01]

* O administrador atribui um nome a sua reserva.

* O administrador aperta no botão "Efetuar reserva".

* O administrador seleciona marca a opção "reservar espaço para outro usuário".

* O administrador digita o nome do usuário ao qual deseja atribuir a reserva.

* O administrador seleciona o usuário que ao qual deseja atribuir a reserva.

* O administrador é encaminhado ao [FP03] do "Criar Reserva".

#7. Fluxo de Exceção

[FE01] No passo 4 do fluxo principal [FP04] o usuário aperta no botão "cancelar" , retorna para [FP01].

[FE02] No passo 4 do [FA02] o administrador digita o nome de um usuário que não existe, retorna para [FA02] sinalizando que o usuário digitado não existe.


[retornar para Especificações de Caso de Uso](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Uso)