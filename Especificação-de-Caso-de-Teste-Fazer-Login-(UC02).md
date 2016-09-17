[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)



Testes referentes ao login de usuários:  
* **TC01 - Todos os campos válidos**  
    Descrição: Este caso de teste tem como objetivo permitir o login de usuários.  
    Pré-condição: Usuário informou nome de usuário e senha válidos, está cadastrado no banco de dados.  
    Pós-condição: Usuário fez login no sistema.  
    Dados: Nome de usuário e senha.   

* **TC02 - Usuário informou dados válidos, mas não está cadastrado no sistema**  
    Descrição: Este caso de teste tem como objetivo impedir o login de usuários não cadastrados no sistema.  
    Pré-condição: Usuário informou nome de usuário e senha válidos e não está cadastrado no banco de dados.  
    Pós-condição: Mensagem de erro informando que os dados não constam no banco de dados.  
    Dados: Nome de usuário e senha.  

* **TC03 - Campo 'nome de usuário' nulo**  
    Descrição: Este caso de teste tem o objetivo de impedir o login de usuários caso o campo 'nome de usuário' esteja nulo.  
    Pré-condição: Campo 'nome de usuário' está nulo.  
    Pós-condição: Mensagem de erro informando que o campo está vazio.  
    Dados: Nome de usuário.  

* **TC04 - Campo 'nome de usuário' em branco**  
    Descrição: Este caso de teste tem o objetivo de impedir o login de usuários caso o campo 'nome de usuário' esteja em branco.  
    Pré-condição: Campo 'nome de usuário' está em branco.  
    Pós-condição: Mensagem de erro informando que o campo está em branco.  
    Dados: Nome de usuário.  

* **TC05 - Campo 'senha' nulo**  
    Descrição: Este caso de teste tem o objetivo de impedir o login de usuários caso o campo 'senha' esteja nulo.  
    Pré-condição: Campo 'senha' está nulo.  
    Pós-condição: Mensagem de erro informando que o campo está vazio.  
    Dados: Senha.  


* **TC06 - Campo 'senha' em branco**  
    Descrição: Este caso de teste tem o objetivo de impedir o login de usuários caso o campo 'senha' esteja em branco.  
    Pré-condição: Campo 'senha' está em branco.  
    Pós-condição: Mensagem de erro informando que o campo está em branco.  
    Dados: Senha.  

* **TC07 - Nome de usuário cadastrado no sistema, porém a senha está errada**  
	Descrição: Este teste tem como objetivo impedir o login de usuário quando este informar uma senha errada.  
	Pré-condição: Usuário informou um nome de usuário cadastrado no banco de dados e digitou uma senha errada.  
	Pós-condição: Mensagem de erro informando que a senha está errada.  
	Dados: Nome de usuário e senha.  


[retornar para Especificações de Caso de Teste](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste)