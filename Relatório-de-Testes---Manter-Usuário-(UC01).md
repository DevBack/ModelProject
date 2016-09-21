[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)

#Índice
[1. Cadastrar Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes---Manter-Usu%C3%A1rio-(UC01)#1-cadastrar-usu%C3%A1rio)

[2. Editar Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes---Manter-Usu%C3%A1rio-(UC01)#2-editar-usu%C3%A1rio)

[3. Pesquisar Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes---Manter-Usu%C3%A1rio-(UC01)#3-pesquisar-usu%C3%A1rio)

[4. Excluir Usuário](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes---Manter-Usu%C3%A1rio-(UC01)#4-excluir-usu%C3%A1rio)
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

![TC 01](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc01.png)

##TC02 - Todos os campos inválidos
### Operação 
Preenchimento de todos os campos inválidos para cadastro de usuário.
### Dados Utilizados
Nome, matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que os campos estão vazios e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o primeiro campo não foi preenchido.

![TC 02](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc02.png)


##TC03 - Campo ‘nome’ vazio
### Operação 
Campo nome vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de nome está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de nome não foi preenchido.

![TC 03](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc03_04.png)


##TC04 - Campo ‘nome’ nulo
### Operação 
Campo nome nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Matrícula, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de nome está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de nome não foi preenchido.


![TC 03](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc03_04.png)

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

![TC 06](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc06_07.png)

##TC07 - Campo ‘matrícula’ nulo
### Operação 
Campo matrícula nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, e-mail, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de matrícula está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de matrícula não foi preenchido.

![TC 07](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc06_07.png)

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

![TC 10](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc10_11.png)

##TC11 - Campo ‘e-mail’ nulo
### Operação 
Campo email nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de email está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem informando que o campo de email não foi preenchido.

![TC 10](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc10_11.png)

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
Exceção(IntegrityError).

![TC 10](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc13.png)

##TC14 - Campo ‘senha’ vazio
### Operação 
Campo senha vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial.


##TC15 - Campo ‘senha’ nulo
### Operação 
Campo senha nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, repetir senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Retorno a página inicial.

##TC16 - Campo ‘confirmar senha’ vazio
### Operação 
Campo confirmar senha vazio e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem de erro informando que o campo de confirmar senha está vazio.

![TC 16](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/tc1617.png)

##TC17 - Campo ‘confirmar senha’ nulo
### Operação 
Campo confirmar senha nulo e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail, senha.
### Resultado esperado
Mensagens de erro informando que o campo de senha está vazio e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem de erro informando que o campo de confirmar senha está vazio.

![TC 17](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/tc1617.png)

##TC18 - Campo ‘senha’ e ‘confirmar senha’ não correspondem
### Operação 
Campo confirmar senha e senha não correspondentes e preenchimento válido dos outros campos.
### Dados Utilizados
Nome, matrícula, e-mail,senha, repetir senha.
### Resultado esperado
Mensagens de erro informando que os campos de senha e de confirma senha não conferem e que o usuário não foi cadastrado. 
### Resultado obtido
Mensagem de erro informando que os campos de senha e de confirma senha não conferem.

![TC 18](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc01_tc18.png)

#2. Editar Usuário  
##TC19 - Alterar nome  
### Operação  
Campo nome alterado e preenchimento válido para os outros campos.  
### Dados utilizados  
Nome.
### Resultado esperado  
Mensagem de sucesso informando que o campo nome foi alterado com sucesso.  
### Resultado obtido  
Campo nome alterado e mensagem informando que os dados foram atualizados.

![TC 19](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_tc19.png)

##TC20 - Campo nome vazio  
### Operação  
Campo nome vazio e preenchimento válido para os outros campos.  
### Dados utilizados  
Não há.
### Resultado esperado  
Mensagem de erro informando que o campo nome deve ser preenchido.  
### Resultado obtido  
Mensagem pedindo para usuário preencher o campo.

![TC 20](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_tc20_21.png)

##TC21 - Campo nome nulo  
### Operação  
Campo nome nulo e preenchimento válido para os outros campos.  
### Dados utilizados  
Não há.
### Resultado esperado  
Mensagem de erro informando que o campo ‘nome’ deve ser preenchido.  
### Resultado obtido  
Mensagem pedindo para usuário preencher o campo.

![TC 21](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_tc20_21.png)

##TC22 - Campo nome inválido  
### Operação  
Campo nome inválido e preenchimento válido para os outros campos.  
### Dados utilizados  
Nome.
### Resultado esperado  
Mensagem de erro informando que o campo nome possui caracteres inválido.  
### Resultado obtido  
Nome alterado e mensagem informando que os dados foram atualizados.

##TC23 - Alterar e-mail
### Operação  
Campo e-mail alterado e preenchimento válido para os outros campos.  
### Dados utilizados  
E-mail.
### Resultado esperado  
Mensagem de sucesso informando que o e-mail foi alterado com sucesso.  
### Resultado obtido  
E-mail alterado e mensagem informando que os dados foram atualizados.

##TC24 - Campo e-mail vazio
### Operação  
Campo e-mail vazio e preenchimento válido para os outros campos.  
### Dados utilizados  
Não há.
### Resultado esperado  
Mensagem de erro informando que o campo e-mail deve ser preenchido.  
### Resultado obtido  
Mensagem pedindo para usuário preencher o campo.

![TC 24](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_tc24_25.png)

##TC25 - Campo e-mail nulo  
### Operação  
Campo nulo vazio e preenchimento válido para os outros campos.  
### Dados utilizados  
E-mail.
### Resultado esperado  
Mensagem de erro informando que o campo e-mail deve ser preenchido.  
### Resultado obtido  
Mensagem pedindo para usuário preencher o campo.

![TC 25](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_tc24_25.png)

##TC26 - E-mail informado já consta no banco de dados  
### Operação  
E-mail já cadastrado preenchimento válido para os outros campos.  
### Dados utilizados  
E-mail.
### Resultado esperado  
Mensagem de erro informando que já existe um usuário cadastrado com aquele e-mail.  
### Resultado obtido  
E-mail não alterado e mensagem informando que o e-mail já está sendo utilizado.

![TC 26](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_tc26.png)

##TC27 - Alterar senha  
### Operação  
Preenchimentos da senha atual, da nova senha e da confirmação de senha.  
### Dados utilizados  
Senha atual, nova senha e confirmação da nova senha.  
### Resultado esperado  
Mensagem de sucesso informando que a senha foi alterada com sucesso.  
### Resultado obtido  
Senha alterada e mensagem informando que a senha foi atualizada.

![TC 27](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02_t27.png)

##TC28 - Senha atual incorreta  
### Operação  
Preenchimentos da senha atual incorreta.  
### Dados utilizados  
Senha.  
### Resultado esperado  
Mensagem de erro informando que a senha atual foi digitada incorretamente.  
### Resultado obtido  
Senha não alterada e mensagem informando que a senha está errada.

##TC29 - Confirmação de nova senha incompatível com a nova senha  
### Operação  
Preenchimentos da nova senha diferente da confirmação de senha.  
### Dados  
Senha atual, nova senha, confirmação de nova senha.    
### Resultado esperado  
Mensagem de erro informando que as senhas não conferem.  
### Resultado obtido  
Senha não alterada e mensagem informando que as senhas não conferem.  

##TC30 - Campo senha vazio  
### Operação  
Campo senha atual vazio.  
### Dados  
Não há.  
### Resultado esperado  
Mensagem de erro informando que o campo senha deve ser preenchido.  
### Resultado obtido  
Senha não alterada e mensagem pedindo para o usuário preencher o campo.  

##TC31 - Campo senha nulo  
### Operação  
Campo senha atual nulo.  
### Dados  
Não há.  
### Resultado esperado  
Mensagem de erro informando que o campo senha deve ser preenchido.  
### Resultado obtido  
Senha não alterada e mensagem pedindo para o usuário preencher o campo.

**OBS.:** Durante os testes foi observado que não é possível alterar o mesmo dado duas vezes. Ao fazê-lo ocorre o logout do usuário e não é possível fazer o login novamente - o sistema informa que o e-mail ou a senha estão errados.

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

![TC 36](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/tc36.png)
##TC37 - Usuário não confirmou a exclusão de sua conta
### Operação 
Impedir a exclusão da conta de usuário após a não confirmação.
### Dados Utilizados
Não há.
### Resultado esperado
O usuário permanece na página de seus dados. 
### Resultado obtido
Não há confirmação.

[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)