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
|08/09/2016 |1.7 |Atualização Casos de Testes Cadastrar Usuário e Excluir Usuário|Vítor |

#1. Introdução

#2. Especificação dos Casos de Teste
Nesta seção serão descritas as condições necessárias para a realização dos teste, assim como os resultados esperados.
##2.1. Manter Usuário
###2.1.1. Cadastrar Usuário
Testes referentes ao cadastro de usuários:
* **Todos os campos válidos**  
    Descrição: Este caso de teste tem como objetivo cadastrar o usuário.  
    Pré-condições: o usuário não está cadastrado, todos os campos são válidos e botão cadastrar foi acionado.  
    Pós-condições: mensagem de cadastrado efetuado com sucesso e cadastro armazenado no banco de dados.  
    Dados necessários: nome, matrícula, e-mail, senha.

* **Todos os campos inválidos**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário quando todos os campos estão inválidos.  
    Pré-condições: O usuário não está cadastrado, todos os campos estão são inválidos e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que os campos estão vazios e que o usuário não foi cadastrado.  
    Dados necessários: Nome, matrícula, e-mail, senha.  
  
* **Campo ‘nome’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'nome' esteja vazio.  
    Pré-condições: O usuário não está cadastrado, campo ‘nome’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘nome’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'nome' esteja nulo.  
    Pré-condições: O usuário não está cadastrado, campo ‘nome’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘nome’ inválido**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'nome' esteja inválido.  
    Pré-condições: O usuário não está cadastrado, campo ‘nome’ contém caracteres inválidos e o botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo contém caracteres inválidos e que o usuário não foi cadastrado.  
    Dados necessários: Nome.  

* **Campo ‘matrícula’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja vazio.    
    Pré-condições: O usuário não está cadastrado, campo ‘matrícula’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘matrícula’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja nulo.    
    Pré-condições: O usuário não está cadastrado, campo ‘matrícula’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está nulo e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘matrícula’ inválido**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja inválido.    
    Pré-condições: O usuário não está cadastrado, campo ‘matrícula’ contém caracteres inválidos e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo contém caracteres inválidos e que o usuário não foi cadastrado.  
    Dados necessários: Matrícula.  

* **Matrícula informada já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso a matrícula informada já esteja cadastrada no banco de dados.      
    Pré-condições: O usuário não está cadastrado, informou uma matrícula já cadastrada e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que a matrícula já existe e que o usuário não foi cadastrado.  
    Dados necessários: Matrícula.  

* **Campo ‘e-mail’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja vazio.      
    Pré-condições: O usuário não está cadastrado, campo ‘e-mail’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘e-mail’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'matrícula' esteja nulo.      
    Pré-condições: O usuário não está cadastrado, campo ‘e-mail’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘e-mail’ inválido**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'e-mail' esteja inválido.       
    Pré-condições: O usuário não está cadastrado, informou um e-mail inválido e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está preenchido incorretamente e que o usuário não foi cadastrado.  
    Dados necessários: E-mail.  

* **E-mail informado já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso seja informado um e-mail já cadastrado no banco de dados.  
    Pré-condições: O usuário não está cadastrado, informou um e-mail já cadastrado e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que já existe e que o usuário não foi cadastrado.  
    Dados necessários: E-mail.  

* **Campo ‘senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'senha' esteja vazio.       
    Pré-condições: O usuário não está cadastrado, campo ‘senha’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘senha’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'senha' esteja nulo.       
    Pré-condições: O usuário não está cadastrado, campo ‘senha’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está nulo e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘confirmar senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'confirmar senha' esteja vazio.       
    Pré-condições: O usuário não está cadastrado, campo ‘confirmar senha’ está vazio e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘confirmar senha’ nulo**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso o campo 'confirmar senha' esteja nulo.       
    Pré-condições: O usuário não está cadastrado, campo ‘confirmar senha’ está nulo e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que o campo está nulo e que o usuário não foi cadastrado.  
    Dados necessários: Não há.  

* **Campo ‘senha’ e ‘confirmar senha’ não correspondem**  
    Descrição: Este caso de teste tem como objetivo impedir o cadastro do usuário caso os dados dos campos 'senha' e 'confirmar senha' sejam diferentes.  
    Pré-condições: O usuário não está cadastrado, campo ‘senha’ e ‘confirmar senha’ não correspondem e botão cadastrar foi acionado.  
    Pós-condições: Mensagens de erro informando que as senhas não correspondem e que o usuário não foi cadastrado.  
    Dados necessários: Senha, confirmação de senha.  

### 2.1.2 Editar usuário

Testes referentes à edição de um usuário:


* **Alterar nome**  
    Descrição: Este caso de teste tem como objetivo alterar o nome do usuário cadastrado no sistema.  
    Pré-condição: O usuário deve estar logado no sistema e tentar alterar seu nome informando um nome válido.  
    Pós-condição: O sistema deve mostrar uma mensagem de sucesso informando que o nome foi alterado com sucesso.   
    Dados necessários: Nome.  

* **Campo ‘nome’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome vazio.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ em branco.   
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ deve ser preenchido.   
    Dados necessários: Não há.       

* **Campo ‘nome’ nulo**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome nulo.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ nulo.   
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ deve ser preenchido.   
    Dados necessários: Não há.  
  
* **Campo ‘nome’ inválido**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome com caracteres especiais e/ou números.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ preenchido com caracteres especiais e/ou números.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ possui caracteres inválido.  
    Dados necessários: Nome.  
  
* **Alterar e-mail**  
    Descrição: Este caso de teste tem como objetivo alterar o e-mail do usuário cadastrado no sistema.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar seu e-mail informando um e-mail válido.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que o e-mail foi alterado com sucesso.
    Dados necessários: E-mail.  
  
* **Campo ‘e-mail’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um e-mail vazio.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘e-mail’ em branco.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘e-mail’ deve ser preenchido.  
    Dados necessários: Não há.  
  
* **Campo ‘e-mail’ nulo**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um e-mail nulo.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘e-mail’ nulo.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘e-mail’ deve ser preenchido corretamente.  
    Dados necessários: E-mail.  
  
* **E-mail informado já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo garantir que dois usuários não possuam o mesmo e-mail.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro informando um e-mail que já consta no banco de dados.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que já existe um usuário cadastrado com aquele e-mail.  
    Dados necessários: E-mail.  
  
* **Alterar senha**  
    Descrição: Este caso de teste tem como objetivo alterar a senha do usuário cadastrado no sistema.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual corretamente, a nova senha e sua confirmação são iguais.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados necessários: Senha atual, nova senha e confirmação da nova senha.  
  
* **Senha atual incorreta**  
    Descrição: Este caso de teste tem como objetivo impedir a alteração da senha usuário.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual incorretamente.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que a senha atual foi digitada incorretamente.  
    Dados necessários: Senha.  

* **Confirmação de nova senha incompatível com a nova senha**  
    Descrição: Este caso de teste tem como objetivo impedir a alteração da senha usuário quando a nova senha e sua confirmação não são iguais.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual, são informados dados diferentes nos campos de 'nova senha' e 'confirmação de nova senha'.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados necessários: Senha atual, nova senha, confirmação de nova senha.  
  
* **Campo ‘senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua uma senha vazia.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘senha’ em branco.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘senha’ deve ser preenchido.  
    Dados necessários: Não há.  

* **Campo ‘senha’ nulo**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua uma senha nula.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘senha’ nulo.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘senha’ deve ser preenchido.  
    Dados necessários: Não há.  

###2.1.3. Excluir usuário  
Testes referentes à exclusão de usuário:  

* **Usuário deseja excluir sua conta**  
	Descrição: Este caso de teste tem como objetivo mostrar uma mensagem de confirmação de exclusão quando o usuário deseja excluir sua conta.  
	Pré-condições: Usuário fez login, e selecionou o botão excluir conta.  
	Pós-condições: Mensagem de confirmação de exclusão de conta.  

* **Usuário confirmou a exclusão de sua conta**  
	Descrição: Este caso de teste tem como objetivo excluir a conta do usuário.  
	Pré-condições: Usuário fez login, selecionou o botão excluir conta e confirmou a exclusão.  
	Pós-condições: Mensagem de sucesso de exclusão e usuário não está no banco de dados.  

* **Usuário não confirmou a exclusão de sua conta**  
	Descrição: Este caso de teste tem como objetivo impedir a exclusão da conta caso o usuário não confirme a exclusão.  
	Pré-condições: Usuário fez login, selecionou o botão excluir conta e não confirmou a exclusão.  
	Pós-condições: O usuário ainda consta no banco de dados.  

###2.1.4. Pesquisar Usuário  
Testes referentes à pesquisa de usuários:

* **Usuário pesquisou um nome que possui no banco de dados**  
	Descrição: Este caso de teste tem como objetivo listar os usuários que correspondam ao nome pesquisado.
	Pré-condições: Usuário fez login, preencheu o campo de pesquisa corretamente e selecionou o botão pesquisar.  
	Pós-condições: Todos os nomes pesquisados listados.  
	Dados necessários: nome a ser pesquisado ou parte do nome.  

* **Campo de pesquisa inválido**  
	Descrição: Este caso de teste tem como objetivo impedir a pesquisa quando o campo de pesquisa possui caracteres inválidos.  
	Pré-condições: Usuário fez login, preencheu o campo de pesquisa incorretamente e selecionou o botão pesquisar.  
	Pós-condições: Mensagem de erro informando que o campo foi preenchido incorretamente.  
	Dados necessários: Nome a ser pesquisado ou parte do nome.   

* **Nome pesquisado não consta no banco de dados**  
        Descrição: Este caso de teste tem como objetivo informar que não há nenhum usuário cadastrado quando a pesquisa não encontra nenhum nome correspondente no banco de dados.
	Pré-condições: Usuário fez login, preencheu o campo de pesquisa corretamente com um nome que não foi cadastrado e selecionou o botão pesquisar.  
	Pós-condiçõess: Mensagem  informando que não possui um usuário com o nome pesquisado.  
	Dados necessários: Nome a ser pesquisado ou parte do nome.   