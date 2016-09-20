#Índice

#1. Cadastrar Usuário
##TC01 - Todos os campos válidos
### Operação 
Preenchimento de todos os campos válidos para cadastro de usuário.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Retorno a página inicial, mensagem de sucesso no cadastro e cadastro armazenado no banco de dados. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.

##TC02 - Todos os campos inválidos
### Operação 
Preenchimento de todos os campos inválidos para cadastro de usuário.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que os campos estão vazios e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o primeiro campo não foi preenchido.

##TC03 - Campo ‘nome’ vazio
### Operação 
Campo nome vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de nome está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de nome não foi preenchido.

##TC04 - Campo ‘nome’ nulo
### Operação 
Campo nome nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de nome está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de nome não foi preenchido.

##TC05 - Campo ‘nome’ inválido
### Operação 
Preenchimento inválido do campo nome e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de nome contém caracteres inválidos e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.

##TC06 - Campo ‘matrícula’ vazio
### Operação 
Campo matrícula vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de matrícula está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de matrícula não foi preenchido.

##TC07 - Campo ‘matrícula’ nulo
### Operação 
Campo matrícula nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de matrícula está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de matrícula não foi preenchido.

##TC08 - Campo ‘matrícula’ inválido
### Operação 
Preenchimento inválido do campo matrícula e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de matrícula contém caracteres inválidos e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.

##TC09 - Matrícula informada já consta no banco de dados
### Operação 
Preenchimento do campo matrícula com uma já cadastrada.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o já existe cadastro com a matrícula e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.


##TC10 - Campo ‘e-mail’ vazio
### Operação 
Campo email vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de email está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de email não foi preenchido.

##TC11 - Campo ‘e-mail’ nulo
### Operação 
Campo email nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de email está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de email não foi preenchido.

##TC12 - Campo ‘e-mail’ inválido
### Operação 
Preenchimento inválido do campo email e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de email contém caracteres inválidos e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.

##TC13 - E-mail informado já consta no banco de dados
### Operação 
Preenchimento do campo email com um já cadastrado.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o já existe cadastro com o email e que o usuário não foi cadastrado. 
### Resultado obtido
Exceção(IntegrityErro).

##TC14 - Campo ‘senha’ vazio
### Operação 
Campo senha vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.


##TC15 - Campo ‘senha’ nulo
### Operação 
Campo senha nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial e cadastro armazenado no banco de dados.

##TC16 - Campo ‘confirmar senha’ vazio
### Operação 
Campo confirmar senha vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem de erro informando que o campo de confirmar senha está vazio.

##TC17 - Campo ‘confirmar senha’ nulo
### Operação 
Campo confirmar senha nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem de erro informando que o campo de confirmar senha está vazio.

##TC18 - Campo ‘senha’ e ‘confirmar senha’ não correspondem
### Operação 
Campo confirmar senha e senha não correspondentes e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail,senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que os campos de senha e de confirma senha não conferem e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem de erro informando que os campos de senha e de confirma senha não conferem.
#2. Editar Usuário
#3. Pesquisar Usuário 
#4. Excluir Usuário
##TC35 - Usuário deseja excluir sua conta
### Operação 
Apertar o botão de "excluir conta" para que seja aberta uma confirmação.
### Dados Utilizados
Não há.
### Resultado esperado
Mensagem de confirmação da exclusão da conta. 
### Resultado obtido
Exclusão sem botão de confirmação, retorno a página inicial, porém o usuário continua com acesso mesmo com a conta deletada do banco de dados.

##TC36 - Usuário confirmou a exclusão de sua conta
### Operação 
Excluir a conta de usuário após a confirmação.
### Dados Utilizados
Não há.
### Resultado esperado
Retorno a página inicial, mensagem de sucesso na exclusão da conta e cadastro retirado do banco de dados. 
### Resultado obtido
Não há confirmação.

##TC37 - Usuário não confirmou a exclusão de sua conta
### Operação 
Impedir a exclusão da conta de usuário após a não confirmação.
### Dados Utilizados
Não há.
### Resultado esperado
O usuário permanece na página de seus dados. 
### Resultado obtido
Não há confirmação.