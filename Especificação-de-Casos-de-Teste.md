# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|31/08/2016 |1.0 |Especificação dos Casos de Teste |Lucas |
|01/09/2016 |1.1 |Complementando Especificação dos Casos de Teste |Hugo |
|02/09/2016 |1.2 |Caso de Teste Editar Usuário |Vítor |
|02/09/2016 |1.3 |Atualização Caso de Teste Editar Usuário |Vítor |
|02/09/2016 |1.4 |Casos de Teste Excluir Usuário e Pesquisar Usuário |Lucas |
|02/09/2016 |1.5 |Atualização Caso de Teste Editar Usuário |Vítor |
|08/09/2016 |1.6 |Atualização Caso de Teste Editar Usuário |Vítor |
|08/09/2016 |1.7 |Atualização Casos de Testes Cadastrar Usuário e Excluir Usuário |Vítor |
|09/09/2016 |1.8 |Caso de Teste Criar Reserva e Atualização Caso de Teste Excluir Usuário |Vítor |  
|09/09/2016 |1.9 |Caso de Teste Excluir Reserva |Vítor |
|09/09/2016 |2.0 |Caso de Teste Fazer Login |Lucas |
|13/09/2016 |2.1 |Atualização Caso de Teste Criar Reserva |Vítor |
|16/09/2016 |2.2 |Caso de Teste Consultar Reserva e Atualização Caso de Teste Criar Reserva |Vítor |

#Índice
[Introdução](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste#1-introdu%C3%A7%C3%A3o)

[Manter Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Teste-Manter-Usu%C3%A1rio-(UC01))


[Fazer Login](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Teste-Fazer-Login-(UC02)https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Casos-de-Teste#22-fazer-login)

[Criar Reserva](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Teste-Criar-Reserva-(UC03))

[Consultar Reserva](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Teste-Consultar-Reserva-(UC04))

[Excluir Reserva](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Especifica%C3%A7%C3%A3o-de-Caso-de-Teste-Excluir-Reserva-(UC05))
#1. Introdução
Este documento especifica os testes que devem ser efetuados para cada caso de uso que foi anteriormente especificado.
#2. Especificação dos Casos de Teste
Nesta seção serão descritas as condições necessárias para a realização dos teste, assim como os resultados esperados.
##2.1. UC01 - Manter Usuário
###2.1.1. Cadastrar Usuário
Testes referentes ao cadastro de usuários:
* **TC01 - Todos os campos válidos**  
    Descrição: Este caso de teste tem como objetivo cadastrar o usuário.  
    Pré-condições: o usuário não está cadastrado, todos os campos são válidos e botão cadastrar foi acionado.  
    Pós-condições: mensagem de cadastrado efetuado com sucesso e cadastro armazenado no banco de dados.  
    Dados necessários: nome, matrícula, e-mail, senha.

* **TC02 - Todos os campos inválidos**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário quando todos os campos estão inválidos.  
    Pré-condições: O usuário não está cadastrado, todos os campos estão são inválidos e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que os campos estão vazios e que o usuário não foi cadastrado.  
    Dados necessários: Nome, matrícula, e-mail, senha.  
  
* **TC03 - Campo ‘nome’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'nome' esteja vazio.  
    Pré-condições: O usuário não está cadastrado, campo ‘nome’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC04 - Campo ‘nome’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'nome' esteja nulo.  
    Pré-condições: O usuário não está cadastrado, campo ‘nome’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC05 - Campo ‘nome’ inválido**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'nome' esteja inválido.  
    Pré-condições: O usuário não está cadastrado, campo ‘nome’ contém caracteres inválidos e o botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo contém caracteres inválidos e que o usuário não foi cadastrado.  
    Dados necessários: Nome.  

* **TC06 - Campo ‘matrícula’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja vazio.    
    Pré-condições: O usuário não está cadastrado, campo ‘matrícula’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC07 - Campo ‘matrícula’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja nulo.    
    Pré-condições: O usuário não está cadastrado, campo ‘matrícula’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está nulo e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC08 - Campo ‘matrícula’ inválido**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja inválido.    
    Pré-condições: O usuário não está cadastrado, campo ‘matrícula’ contém caracteres inválidos e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo contém caracteres inválidos e que o usuário não foi cadastrado.  
    Dados necessários: Matrícula.  

* **TC09 - Matrícula informada já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso a matrícula informada já esteja cadastrada no banco de dados.      
    Pré-condições: O usuário não está cadastrado, informou uma matrícula já cadastrada e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que a matrícula já existe e que o usuário não foi cadastrado.  
    Dados necessários: Matrícula.  

* **TC10 - Campo ‘e-mail’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja vazio.      
    Pré-condições: O usuário não está cadastrado, campo ‘e-mail’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC11 - Campo ‘e-mail’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja nulo.      
    Pré-condições: O usuário não está cadastrado, campo ‘e-mail’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC12 - Campo ‘e-mail’ inválido**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'e-mail' esteja inválido.       
    Pré-condições: O usuário não está cadastrado, informou um e-mail inválido e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está preenchido incorretamente e que o usuário não foi cadastrado.  
    Dados necessários: E-mail.  

* **TC13 - E-mail informado já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso seja informado um e-mail já cadastrado no banco de dados.  
    Pré-condições: O usuário não está cadastrado, informou um e-mail já cadastrado e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que já existe e que o usuário não foi cadastrado.  
    Dados necessários: E-mail.  

* **TC14 - Campo ‘senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'senha' esteja vazio.       
    Pré-condições: O usuário não está cadastrado, campo ‘senha’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC15 - Campo ‘senha’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'senha' esteja nulo.       
    Pré-condições: O usuário não está cadastrado, campo ‘senha’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está nulo e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC16 - Campo ‘confirmar senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'confirmar senha' esteja vazio.       
    Pré-condições: O usuário não está cadastrado, campo ‘confirmar senha’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC17 - Campo ‘confirmar senha’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'confirmar senha' esteja nulo.       
    Pré-condições: O usuário não está cadastrado, campo ‘confirmar senha’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está nulo e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **TC18 - Campo ‘senha’ e ‘confirmar senha’ não correspondem**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso os dados dos campos 'senha' e 'confirmar senha' sejam diferentes.  
    Pré-condições: O usuário não está cadastrado, campo ‘senha’ e ‘confirmar senha’ não correspondem e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que as senhas não correspondem e que o usuário não foi cadastrado.  
    Dados necessários: Senha, confirmação de senha.  

### 2.1.2 Editar usuário

Testes referentes à edição de um usuário:


* **TC19 - Alterar nome**  
    Descrição: Este caso de teste tem como objetivo alterar o nome do usuário cadastrado no sistema.  
    Pré-condição: O usuário deve estar logado no sistema e tentar alterar seu nome informando um nome válido.  
    Pós-condição: O sistema deve mostrar uma mensagem de sucesso informando que o nome foi alterado com sucesso.   
    Dados necessários: Nome.  

* **TC20 - Campo ‘nome’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome vazio.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ em branco.   
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ deve ser preenchido.   
    Dados necessários: Não há.       

* **TC21 - Campo ‘nome’ nulo**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome nulo.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ nulo.   
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ deve ser preenchido.   
    Dados necessários: Não há.  
  
* **TC22 - Campo ‘nome’ inválido**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome com caracteres especiais e/ou números.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ preenchido com caracteres especiais e/ou números.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ possui caracteres inválido.  
    Dados necessários: Nome.  
  
* **TC23 - Alterar e-mail**  
    Descrição: Este caso de teste tem como objetivo alterar o e-mail do usuário cadastrado no sistema.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar seu e-mail informando um e-mail válido.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que o e-mail foi alterado com sucesso.
    Dados necessários: E-mail.  
  
* **TC24 - Campo ‘e-mail’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um e-mail vazio.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘e-mail’ em branco.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘e-mail’ deve ser preenchido.  
    Dados necessários: Não há.  
  
* **TC25 - Campo ‘e-mail’ nulo**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um e-mail nulo.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘e-mail’ nulo.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘e-mail’ deve ser preenchido corretamente.  
    Dados necessários: E-mail.  
  
* **TC26 - E-mail informado já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo garantir que dois usuários não possuam o mesmo e-mail.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro informando um e-mail que já consta no banco de dados.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que já existe um usuário cadastrado com aquele e-mail.  
    Dados necessários: E-mail.  
  
* **TC27 - Alterar senha**  
    Descrição: Este caso de teste tem como objetivo alterar a senha do usuário cadastrado no sistema.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual corretamente, a nova senha e sua confirmação são iguais.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados necessários: Senha atual, nova senha e confirmação da nova senha.  
  
* **TC28 - Senha atual incorreta**  
    Descrição: Este caso de teste tem como objetivo impedir a alteração da senha usuário.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual incorretamente.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que a senha atual foi digitada incorretamente.  
    Dados necessários: Senha.  

* **TC29 - Confirmação de nova senha incompatível com a nova senha**  
    Descrição: Este caso de teste tem como objetivo impedir a alteração da senha usuário quando a nova senha e sua confirmação não são iguais.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual, são informados dados diferentes nos campos de 'nova senha' e 'confirmação de nova senha'.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados necessários: Senha atual, nova senha, confirmação de nova senha.  
  
* **TC30 - Campo ‘senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua uma senha vazia.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘senha’ em branco.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘senha’ deve ser preenchido.  
    Dados necessários: Não há.  

* **TC31 - Campo ‘senha’ nulo**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua uma senha nula.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘senha’ nulo.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘senha’ deve ser preenchido.  
    Dados necessários: Não há.  

###2.1.3. Pesquisar Usuário  
Testes referentes à pesquisa de usuários:

* **TC32 - Usuário pesquisou um nome que possui no banco de dados**  
	Descrição: Este caso de teste tem como objetivo listar os usuários que correspondam ao nome pesquisado.
	Pré-condições: Usuário fez login, preencheu o campo de pesquisa corretamente e selecionou o botão pesquisar.  
	Pós-condições: Todos os nomes pesquisados listados.  
	Dados necessários: nome a ser pesquisado ou parte do nome.  

* **TC33 - Campo de pesquisa inválido**  
	Descrição: Este caso de teste tem como objetivo impedir a pesquisa quando o campo de pesquisa possui caracteres inválidos.  
	Pré-condições: Usuário fez login, preencheu o campo de pesquisa incorretamente e selecionou o botão pesquisar.  
	Pós-condições: Mensagem de erro informando que o campo foi preenchido incorretamente.  
	Dados necessários: Nome a ser pesquisado ou parte do nome.   

* **TC34 - Nome pesquisado não consta no banco de dados**  
        Descrição: Este caso de teste tem como objetivo informar que não há nenhum usuário cadastrado quando a pesquisa não encontra nenhum nome correspondente no banco de dados.  
	Pré-condições: Usuário fez login, preencheu o campo de pesquisa corretamente com um nome que não foi cadastrado e selecionou o botão pesquisar.  
	Pós-condiçõess: Mensagem  informando que não possui um usuário com o nome pesquisado.  
	Dados necessários: Nome a ser pesquisado ou parte do nome.   

###2.1.4. Excluir usuário  
Testes referentes à exclusão de usuário:  

* **TC35 - Usuário deseja excluir sua conta**  
	Descrição: Este caso de teste tem como objetivo mostrar uma mensagem de confirmação de exclusão quando o usuário deseja excluir sua conta.  
	Pré-condições: Usuário fez login, e selecionou o botão excluir conta.  
	Pós-condições: Mensagem de confirmação de exclusão de conta.  
        Dados necessários: Não há.  

* **TC36 - Usuário confirmou a exclusão de sua conta**  
	Descrição: Este caso de teste tem como objetivo excluir a conta do usuário.  
	Pré-condições: Usuário fez login, selecionou o botão excluir conta e confirmou a exclusão.  
	Pós-condições: Mensagem de sucesso de exclusão e usuário não está no banco de dados.   
        Dados necessários: Não há.  

* **TC37 - Usuário não confirmou a exclusão de sua conta**  
	Descrição: Este caso de teste tem como objetivo impedir a exclusão da conta caso o usuário não confirme a exclusão.  
	Pré-condições: Usuário fez login, selecionou o botão excluir conta e não confirmou a exclusão.  
	Pós-condições: O usuário ainda consta no banco de dados.   
        Dados necessários: Não há.

##2.2 UC02 - Fazer Login
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

##2.3. UC03 - Criar Reserva 

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

##2.4. UC04 - Consultar Reserva

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
 
##2.5. UC05 - Excluir Reserva

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