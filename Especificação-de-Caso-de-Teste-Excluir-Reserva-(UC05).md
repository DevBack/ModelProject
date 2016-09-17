[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)

Testes referentes à exclusão de uma reserva:
  
* **TC01 - Excluir reserva de espaço**  
    Descrição: Este caso de teste tem como objetivo apresentar uma mensagem de confirmação quando o usuário desejar excluir alguma reserva.  
    Pré-condições: O usuário está logado e tentou excluir uma reserva de espaço preexistente.  
    Pós-condições: Mensagem de confirmação perguntando se o usuário tem certeza que deseja excluir a reserva.  
    Dados necessários: Não há.  

* **TC02 - Confirmação de exclusão de reserva**  
    Descrição: Este caso de teste tem como objetivo excluir uma reserva.   
    Pré-condições: O usuário está logado, tentou excluir uma reserva de espaço preexistente e confirmou sua exclusão.  
    Pós-condições: Mensagem de sucesso informando que a reserva foi excluída.  
    Dados necessários: Não há.  

* **TC03 - Cancelamento de exclusão de reserva**  
    Descrição: Este caso de teste tem como objetivo impedir a exclusão de uma reserva quando o usuário cancela sua exclusão.    
    Pré-condições: O usuário está logado, tentou excluir uma reserva de espaço preexistente e cancelou sua exclusão.  
    Pós-condições: A reserva permanece no banco de dados.  
    Dados necessários: Não há.  

* **TC04 - Exclusão de reserva de outro usuário**  
    Descrição: Este caso de teste tem como objetivo apresentar uma mensagem de confirmação caso o administrador deseje excluir uma reserva que pertença a outro usuário.    
    Pré-condições: O usuário está logado, é administrador e tentou excluir uma reserva de espaço preexistente de outro usuário.  
    Pós-condições: Mensagem de confirmação perguntando se o administrador tem certeza que deseja excluir a reserva.  
    Dados necessários: Não há.  

* **TC05 - Confirmação de exclusão de reserva de outro usuário**  
    Descrição: Este caso de teste tem como objetivo excluir uma reserva de outro usuário pelo administrador.   
    Pré-condições: O usuário está logado, é administrador, tentou excluir uma reserva de espaço preexistente de outro usuário e confirmou sua exclusão.  
    Pós-condições: Mensagem de sucesso informando que a reserva foi excluída.  
    Dados necessários: Não há.  

* **TC06 - Cancelamento de exclusão de reserva de outro usuário**  
    Descrição: Este caso de teste tem como objetivo impedir a exclusão de uma reserva de outro usuário quando o administrador cancela sua exclusão.   
    Pré-condições: O usuário está logado, é administrador, tentou excluir uma reserva de espaço preexistente de outro usuário e cancelou sua exclusão.  
    Pós-condições: A reserva permanece no banco de dados.  
    Dados necessários: Não há.    

[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)