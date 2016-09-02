# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|31/08/2016 |1.0 |Especificação dos Casos de Teste |Lucas |
|01/09/2016 |1.1 |Complementando Especificação dos Casos de Teste |Hugo |

#1.Introdução

#2.Especificação dos Casos de Teste
Nesta seção serão descritas as condições necessárias para a realização dos teste, assim como os resultados esperados.
##2.1.Manter Usuário
###2.1.1.Cadastrar Usuário
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


