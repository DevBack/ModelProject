[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)

Testes referentes à criação de uma reserva:

* **TC01 - Efetuar reserva de sala**  
    Descrição: Este caso de teste tem como objetivo criar uma reserva de sala.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, todos os campos são válidos, a sala ainda não está reservada.  
    Pós-condições: Mensagem de sucesso informando que a sala foi reservada.  
    Dados necessários: Nome da reserva, data de início, data de fim, horário de início, horário de fim, dia(s) da semana, prédio, sala.  

* **TC02 - Todos os campos vazios**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso todos os campos estejam vazios.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, todos os campos estão vazios.   
    Pós-condições: Mensagem de erro informando que os todos os dados devem ser informados.   
    Dados necessários: Não há.  

* **TC03 - Campo 'nome para reserva' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'nome para reserva' esteja vazio.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o nome da reserva está vazio.  
    Pós-condições: Mensagem de erro informando que o nome da reserva deve ser informado.    
    Dados necessários: Não há.  

* **TC04 - Campo 'nome para reserva' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'nome para reserva' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o nome da reserva está nulo.  
    Pós-condições: Mensagem de erro informando que o nome da reserva deve ser informado.    
    Dados necessários: Não há.  

* **TC05 - Campo 'data de início' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'data de início' esteja vazio.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'data de início' está vazio.    
    Pós-condições: Mensagem de erro informando que a data de início deve ser informada.    
    Dados necessários: Não há.  

* **TC06 - Campo 'data de início' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'data de início' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'data de início' está nulo.  
    Pós-condições: Mensagem de erro informando que a data de início deve ser informada.  
    Dados necessários: Não há.  

* **TC07 - Campo 'data de início' inválido**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'data de início' esteja inválido.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'data de início' está inválido.    
    Pós-condições: Mensagem de erro informando que a data de início deve ser informada corretamente.    
    Dados necessários: Data de início.  

* **TC08 - Campo 'data de fim' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'data de fim' esteja vazio.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'data de fim' está vazio.    
    Pós-condições: Mensagem de erro informando que a data de fim deve ser informada.    
    Dados necessários: Não há.  

* **TC09 - Campo 'data de fim' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'data de fim' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo data de fim está nulo.  
    Pós-condições: Mensagem de erro informando que a data de fim deve ser informada.   
    Dados necessários: Não há.  

* **TC10 - Campo 'data de fim' inválido**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'data de fim' esteja inválido.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'data de fim' está inválido.    
    Pós-condições: Mensagem de erro informando que a data de fim deve ser informada corretamente.    
    Dados necessários: Data de fim.  

* **TC11 - Campo 'horário de início' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'horário de início' esteja vazio.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'horário de início' está vazio.    
    Pós-condições: Mensagem de erro informando que o horário de início deve ser informado.    
    Dados necessários: Não há.  

* **TC12 - Campo 'horário de início' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'horário de início' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'horário de início' está nulo.  
    Pós-condições: Mensagem de erro informando que o horário de início deve ser informado.  
    Dados necessários: Não há.  

* **TC13 - Campo 'horário de início' inválido**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'horário de início' esteja inválido.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'horário de início' está inválido.    
    Pós-condições: Mensagem de erro informando que o horário de início deve ser informado corretamente.    
    Dados necessários: Horário de início.  

* **TC14 - Campo 'horário de fim' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'horário de fim' esteja vazio.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'horário de fim' está vazio.    
    Pós-condições: Mensagem de erro informando que o horário de fim deve ser informado.    
    Dados necessários: Não há.  

* **TC15 - Campo 'horário de fim' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'horário de fim' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'horário de fim' está nulo.  
    Pós-condições: Mensagem de erro informando que o horário de fim deve ser informado.  
    Dados necessários: Não há.  

* **TC16 - Campo 'horário de fim' inválido**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'horário de fim' esteja inválido.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'horário de fim' está inválido.    
    Pós-condições: Mensagem de erro informando que o horário de fim deve ser informado corretamente.    
    Dados necessários: Horário de fim.  

* **TC17 - Campo 'prédio' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'prédio' esteja vazio.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'prédio' está vazio.  
    Pós-condições: Mensagem de erro informando que o prédio deve ser informado.  
    Dados necessários: Não há.  
 
* **TC18 - Campo 'prédio' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'prédio' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'prédio' está nulo.  
    Pós-condições: Mensagem de erro informando que o prédio deve ser informado.  
    Dados necessários: Não há.  

* **TC19 - Campo 'espaço' vazio**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'espaço' esteja vazio.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'espaço' está vazio.    
    Pós-condições: Mensagem de erro informando que o espaço deve ser informado.    
    Dados necessários: Não há.  


* **TC20 - Campo 'espaço' nulo**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o campo 'espaço' esteja nulo.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o campo 'espaço' está nulo.  
    Pós-condições: Mensagem de erro informando que o espaço deve ser informado.  
    Dados necessários: Não há.  

* **TC21 - Campos de dias da semana vazios**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso todos os campos de dias da semana estejam vazios.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, todos os dias da semana estão vazios.  
    Pós-condições: Mensagem de erro informando que o dia da semana deve ser informado.  
    Dados necessários: Não há.  

* **TC22 - Campo de dias da semana nulos**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso todos os campos de dias da semana estejam nulos.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, todos os dias da semana estão nulos.  
    Pós-condições: Mensagem de erro informando que o dia da semana deve ser informado.  
    Dados necessários: Não há.  

* **TC23 - Data de fim anterior à data de início**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso a data de fim seja anterior à data de início.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, a data de fim é anterior à data de início.    
    Pós-condições: Mensagem de erro informando que a data de fim deve ser posterior à data de início.    
    Dados necessários: Data de início, data de fim.  

* **TC24 - Horário de fim anterior ao horário de início**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso o horário de fim seja anterior ao horário de início.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, o horário de fim é anterior ao horário de início.    
    Pós-condições: Mensagem de erro informando que o horário de fim deve ser posterior ao horário de início.    
    Dados necessários: Horário de início, horário de fim.  

* **TC25 - Data de início anterior à data atual**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso a data de início seja anterior à data atual.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, a data de início é anterior à data atual.  
    Pós-condições: Mensagem de erro informando que a data de início deve ser posterior à data atual.  
    Dados necessários: Data de início.  

* **TC26 - Data de fim anterior à data atual**  
    Descrição: Este caso de teste tem como objetivo impedir uma reserva de sala caso a data de fim seja anterior à data atual.  
    Pré-condições: O usuário está logado e tentou efetuar a reserva de uma sala, a data de fim é anterior à data atual.  
    Pós-condições: Mensagem de erro informando que a data de fim deve ser posterior à data atual.  
    Dados necessários: Data de fim.  

* **TC27 - Efetuar pedido de reserva de laboratório**  
    Descrição: Este caso de teste tem como objetivo realizar o pedido de reserva de um laboratório.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de um laboratório.  
    Pós-condições: Mensagem de sucesso informando que o pedido de reserva foi enviado ao administrador.    
    Dados necessários: Nome da reserva, data de início, data de fim, horário de início, horário de fim, dia(s) da semana, prédio, laboratório.   

* **TC28 - Aceitar pedido de reserva de laboratório**  
    Descrição: Este caso de teste tem como objetivo aceitar o pedido de reserva de um laboratório.    
    Pré-condições: O usuário é administrador, está logado e tentou aceitar a reserva de um laboratório.  
    Pós-condições: Mensagem de sucesso informando que o pedido de reserva foi aceita e a reserva do usuário realizada.    
    Dados necessários: Não há.     

* **TC29 - Efetuar reserva de espaço em nome de outro usuário**  
    Descrição: Este caso de teste tem como objetivo criar a reserva de um espaço pelo administrador em nome de outro usuário.    
    Pré-condições: O usuário é um administrador, está logado e tentou efetuar a reserva de um espaço, todos os campos são válidos, o espaço ainda não está reservado.    
    Pós-condições: Mensagem de sucesso informando que o espaço foi reservado.    
    Dados necessários: Nome da reserva, data de início, data de fim, horário de início, horário de fim, dia(s) da semana, prédio, espaço, nome do usuário da reserva.  

* **TC30 - Tentativa de efetuar reserva de espaço em nome de um usuário inexistente**  
    Descrição: Este caso de teste tem como objetivo impedir a reserva de um espaço pelo administrador em nome de outro usuário, caso este usuário não exista.  
    Pré-condições: O usuário é um administrador, está logado e tentou efetuar a reserva de um espaço, todos os campos são válidos, o espaço ainda não está reservado, o usuário informado não existe.  
    Pós-condições: Mensagem de erro informando que o usuário não existe.  
    Dados necessários: Nome da reserva, data de início, data de fim, horário de início, horário de fim, dia(s) da semana, prédio, espaço, nome do usuário da reserva.  

* **TC31 - Espaço já reservado**  
    Descrição: Este caso de teste tem como objetivo impedir a reserva de espaço quando este já está reservado nos horários e datas informados.    
    Pré-condições: O usuário está logado e tentou efetuar a reserva de um espaço já reservado, todos os campos são válidos.   
    Pós-condições: Mensagem de erro informando que o espaço já está reservado.    
    Dados necessários: Nome da reserva, data de início, data de fim, horário de início, horário de fim, dia(s) da semana, prédio, espaço.   


[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)