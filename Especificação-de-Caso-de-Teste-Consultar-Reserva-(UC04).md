[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)

Testes referentes à consulta de uma reserva:

* **TC01 - Listagem de todas as reservas**    
    Descrição: Este caso de teste tem como objetivo listar todas as reservas de sala feitas pelo usuário.  
    Pré-condições: O usuário está logado, o botão 'Minhas Reservas' foi acionado.  
    Pós-condições: São listadas todas as reservas feitas pelo usuário.   
    Dados necessários: Não há.  

* **TC02 - Consulta de reserva específica**  
    Descrição: Este caso de teste tem como objetivo apresentar os dados de uma reserva específica.  
    Pré-condições: O usuário está logado, na página de 'Minhas Reservas' o botão da lupa de alguma das reservas listadas foi acionado.  
    Pós-condições: Todos os dados referentes à reserva são apresentados, como nome da reserva, prédio, sala, data de início, data de fim, horário de início, data de fim e dias da semana.  
    Dados necessários: Não há.  

* **TC03 - Consulta por nome da reserva**  
    Descrição: Este caso de teste tem como objetivo listar todas as reservas de sala feitas pelo usuário que contenham o nome da reserva informado.  
    Pré-condições: O usuário está logado, na página de 'Minhas Reservas', o usuário informou um nome da reserva e o botão 'Consultar' foi acionado.  
    Pós-condições: São listadas todas as reservas feitas pelo usuário que contenham o nome da reserva informado.  
    Dados necessários: Nome da reserva.  

* **TC04 - Consulta por data de reserva**  
    Descrição: Este caso de teste tem como objetivo listar todas as reservas de sala feitas pelo usuário que possuam a data de reserva informada.  
    Pré-condições: O usuário está logado, na página de 'Minhas Reservas', o usuário informou uma data de reserva e o botão 'Consultar' foi acionado.  
    Pós-condições: São listadas todas as reservas feitas pelo usuário que possuam a data de reserva informado.  
    Dados necessários: Data de reserva.   

* **TC05 - Nome da reserva e data de reserva vazios**  
    Descrição: Este caso de teste tem como objetivo listar todas as reservas de sala feitas pelo usuário caso os campos 'nome da reserva' e 'data de reserva' estejam vazios.  
    Pré-condições: O usuário está logado, na página de "Minhas Reservas",  o botão "Consultar" foi acionado e os campos 'nome da reserva' e 'data de reserva' estão vazios.  
    Pós-condições: São listadas todas as reservas feitas pelo usuário.  
    Dados necessários: Não há.  

* **TC06 - Nome da reserva e data de reserva nulos**  
    Descrição: Este caso de teste tem como objetivo listar todas as reservas de sala feitas pelo usuário caso os campos 'nome da reserva' e 'data de reserva' estejam nulos.  
    Pré-condições: O usuário está logado, na página de "Minhas Reservas", o botão "Consultar" foi acionado e os campos 'nome da reserva' e 'data de reserva' estão nulos.  
    Pós-condições: São listadas todas as reservas feitas pelo usuário.  
    Dados necessários: Não há.  

* **TC07 - Listagem de reservas de outro usuário**  
    Descrição: Este caso de teste tem como objetivo listar para um administrador todas as reservas de sala feitas por um outro usuário.  
    Pré-condições: O usuário está logado, é administrador, informou um nome de usuário e o botão 'Visualizar Reservas' foi acionado.  
    Pós-condições: São listadas todas as reservas feitas pelo usuário informado.  
    Dados necessários: Nome de usuário.  

* **TC08 - Usuário informado inexistente**  
    Descrição: Este caso de teste tem como objetivo impedir a listagem para um administrador de todas as reservas de sala feitas por um outro usuário, caso este usuário não exista.  
    Pré-condições: O usuário está logado, é administrador, informou um nome de usuário que não consta no banco de dados e o botão 'Visualizar Reservas' foi acionado.  
    Pós-condições: Mensagem de erro informando que o usuário não existe.  
    Dados necessários: Nome de usuário.   
 

[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)