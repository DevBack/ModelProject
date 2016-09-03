# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|31/08/2016 |1.0 |Especificação dos Casos de Teste |Lucas |
|01/09/2016 |1.1 |Complementando Especificação dos Casos de Teste |Hugo |
|02/09/2016 |1.2 |Caso de Teste Editar Usuário |Vítor |
|02/09/2016 |1.3 |Atualização Caso de Teste Editar Usuário |Vítor |
|02/09/2016 |1.4 |Casos de Teste Excluir Usuário e Pesquisar Usuário |Lucas |
|02/09/2016 |1.5 |Atualização Caso de Teste Editar Usuário |Vítor |

#1. Introdução

#2. Especificação dos Casos de Teste
Nesta seção serão descritas as condições necessárias para a realização dos teste, assim como os resultados esperados.
##2.1. Manter Usuário
###2.1.1. Cadastrar Usuário
Testes referentes ao cadastro de usuários:
* **Campos preenchidos corretamente**  
    Descrição: neste caso todos os campos são preenchidos corretamente.  
    Pré-condição: o usuário não está cadastrado, todos os campos estão preenchidos corretamente e botão cadastrar foi acionado.  
    Pós-condição: mensagem de cadastrado efetuado com sucesso e cadastro armazenado no banco de dados.  
    Dados necessários: nome, matrícula, e-mail, senha.

* **Todos os campos não preenchidos**  
    Descrição: neste caso todos os campos estão em branco.  
    Pré-condição: o usuário não está cadastrado, todos os campos estão em branco e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que os campos estão vazios e que o usuário não foi cadastrado.  
    Dados necessários: nome, matrícula, e-mail, senha.  
  
* **Campo ‘nome’ não preenchido**  
    Descrição: usuário não informou seu nome.  
    Pré-condição: o usuário não está cadastrado, campo ‘nome’ não está preenchido e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: nome.  

* **Campo ‘nome’ preenchido incorretamente**  
    Descrição: usuário informou caracteres especiais e/ou numéricos no campo ‘nome’.  
    Pré-condição: o usuário não está cadastrado, campo ‘nome’ contém caracteres inválidos e obotão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo contém caracteres inválidos e que o usuário não foi cadastrado.  
    Dados necessários: nome.  

* **Campo ‘matrícula’ não preenchido**  
    Descrição: usuário não informou sua matrícula.  
    Pré-condição: o usuário não está cadastrado, campo ‘matrícula’ não está preenchido e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: matrícula.  

* **Campo ‘matrícula’ preenchido incorretamente**  
    Descrição: usuário informou caracteres especiais e/ou alfabéticos no campo ‘matrícula’.  
    Pré-condição: o usuário não está cadastrado, campo ‘matrícula’ contém caracteres inválidos e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo contém caracteres inválidos e que o usuário não foi cadastrado.  
    Dados necessários: matrícula.  

* **Matrícula informada já consta no banco de dados**  
    Descrição: usuário informou uma matrícula que já foi cadastrada.  
    Pré-condição: o usuário não está cadastrado, informou uma matrícula já cadastrada e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que a matrícula já existe e que o usuário não foi cadastrado.  
    Dados necessários: matrícula.  
* **Campo ‘e-mail’ não preenchido**  
    Descrição: usuário não informou seu e-mail.  
    Pré-condição: o usuário não está cadastrado, campo ‘e-mail’ não está preenchido e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: e-mail.  

* **Campo ‘e-mail’ preenchido incorretamente**  
    Descrição: usuário informou um e-mail inválido.  
    Pré-condição: o usuário não está cadastrado, informou um e-mail inválido e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo está preenchido incorretamente e que o usuário não foi cadastrado.  
    Dados necessários: e-mail.  

* **E-mail informado já consta no banco de dados**  
    Descrição: usuário informou um e-mail que já foi cadastrado.  
    Pré-condição: o usuário não está cadastrado, informou um e-mail já cadastrado e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que já existe e que o usuário não foi cadastrado.  
    Dados necessários: e-mail.  

* **Campo ‘senha’ não preenchido**  
    Descrição: usuário não informou sua senha.  
    Pré-condição: o usuário não está cadastrado, campo ‘senha’ não está preenchido e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: senha.  

* **Campo ‘confirmar senha’ não preenchido**  
Descrição: usuário não confirmou sua senha.  
    Pré-condição: o usuário não está cadastrado, campo ‘confirmar senha’ não está preenchido e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que o campo está vazio e que o usuário não foi cadastrado.  
    Dados necessários: senha.  

* **Campo ‘senha’ e ‘confirmar senha’ não correspondem**  
    Descrição: usuário digitou uma senha e confirmou outra.  
    Pré-condição: o usuário não está cadastrado, campo ‘senha’ e ‘confirmar senha’ não correspondem e botão cadastrar foi acionado.  
    Pós-condição: mensagens de erro informando que as senhas não correspondem e que o usuário não foi cadastrado.  
    Dados necessários: senha.  

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
    Dados requeridos: Não há.       
  
* **Campo ‘nome’ inválido**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um nome com caracteres especiais e/ou números.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘nome’ preenchido com caracteres especiais e/ou números.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘nome’ possui caracteres inválido.  
    Dados requeridos: Nome.  
  
* **Alterar e-mail**  
    Descrição: Este caso de teste tem como objetivo alterar o e-mail do usuário cadastrado no sistema.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar seu e-mail informando um e-mail válido.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que o e-mail foi alterado com sucesso.
    Dados requeridos: E-mail.  
  
* **Campo ‘e-mail’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um e-mail vazio.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘e-mail’ em branco.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘e-mail’ deve ser preenchido.  
    Dados requeridos: Não há.  
  
* **Campo ‘e-mail’ inválido**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua um e-mail inválido.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘e-mail’ inválido.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘e-mail’ deve ser preenchido corretamente.  
    Dados requeridos: E-mail.  
  
* **E-mail informado já consta no banco de dados**  
    Descrição: Este caso de teste tem como objetivo garantir que dois usuários não possuam o mesmo e-mail.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro informando um e-mail que já consta no banco de dados.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que já existe um usuário cadastrado com aquele e-mail.  
    Dados requeridos: E-mail.  
  
* **Alterar senha**  
    Descrição: Este caso de teste tem como objetivo alterar a senha do usuário cadastrado no sistema.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual corretamente, a nova senha e sua confirmação são iguais.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados requeridos: Senha atual, nova senha e confirmação da nova senha.  
  
* **Senha atual incorreta**  
    Descrição: Este caso de teste tem como objetivo impedir a alteração da senha usuário.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual incorretamente.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados requeridos: Senha.  

* **Confirmação de nova senha incompatível com a nova senha**  
    Descrição: Este caso de teste tem como objetivo impedir a alteração da senha usuário quando a nova senha e sua confirmação não são iguais.  
    Pré-condições: O usuário deve estar logado no sistema e tentar alterar sua senha informando a senha atual, são informados dados diferentes nos campos de 'nova senha' e 'confirmação de nova senha'.  
    Pós-condições: O sistema deve mostrar uma mensagem de sucesso informando que a senha foi alterada com sucesso.  
    Dados requeridos: Senha atual, nova senha, confirmação de nova senha.  
  
* **Campo ‘senha’ vazio**  
    Descrição: Este caso de teste tem como objetivo garantir que o usuário não possua uma senha vazia.  
    Pré-condições: O usuário deve estar logado no sistema e tentar atualizar seu cadastro com o campo ‘senha’ em branco.  
    Pós-condições: O sistema deve mostrar uma mensagem de erro informando que o campo ‘senha’ deve ser preenchido.  
    Dados requeridos: Não há.  

###2.1.3. Excluir usuário  
Testes referentes à exclusão de usuário:  

* **Usuário deseja excluir sua conta**  
	Descrição: usuário deseja excluir sua conta.  
	Pré-condição: usuário fez login, e selecionou o botão excluir conta.  
	Pós-condição: mensagem de confirmação de exclusão de conta.  

* **Usuário confirmou a exclusão de sua conta**  
	Descrição: usuário excluiu sua conta.  
	Pré-condição: usuário fez login, selecionou o botão excluir conta e confirmou a exclusão.  
	Pós-condição: mensagem de sucesso de exclusão e usuário não está no banco de dados.  

* **Usuário não confirmou a exclusão de sua conta**  
	Descrição: usuário selecionou o botão excluir conta e não confirmou a exclusão.  
	Pré-condição: usuário fez login, selecionou o botão excluir conta e não confirmou a exclusão.  
	Pós-condição: o usuário ainda consta no banco de dados.  

###2.1.4. Pesquisar Usuário  
Testes referentes à pesquisa de usuários:

* **Usuário pesquisou um nome que possui no banco de dados**  
	Descrição: usuário preencheu o campo de pesquisa corretamente e o nome consta no banco de dados.  
	Pré-condição: usuário fez login, preencheu o campo de pesquisa corretamente e selecionou o botão pesquisar.  
	Pós-condição: todos os nomes pesquisados listados.  
	Dado: nome a ser pesquisado ou parte do nome.  

* **Usuário não preencheu o campo de pesquisa corretamente**  
	Descrição: usuário digitou um caracter inválido no campo de pesquisa.  
	Pré-condição: usuário fez login, preencheu o campo de pesquisa incorretamente e selecionou o botão pesquisar.  
	Pós-condição: mensagem de erro informando que o campo foi preenchido incorretamente.  
	Dado: nome a ser pesquisado ou parte do nome.   

* **Usuário preencheu o campo de pesquisa corretamente, porém o nome não consta no banco de dados**  
	Pré-condição: usuário fez login, preencheu o campo de pesquisa corretamente com um nome que não foi cadastrado e selecionou o botão pesquisar.  
	Pós-condição: mensagem  informando que não possui um usuário com o nome pesquisado.  
	Dado: nome a ser pesquisado ou parte do nome.   