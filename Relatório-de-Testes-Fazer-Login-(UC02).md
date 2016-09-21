[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)

##TC01 - Todos os campos válidos
### Operação 
Preenchimento de todos os campos válidos para login de usuário.
### Dados Utilizados
E-mail e senha.  
### Resultado esperado
Usuário fez login no sistema.  
### Resultado obtido
Usuário fez login no sistema.

##TC02 - Usuário informou dados válidos, mas não está cadastrado no sistema  
### Operação  
Preenchimento de todos os campos válidos para login de usuário, porém os dados não estão cadastrados.  
### Dados Utilizados
E-mail e senha.  
### Resultado esperado
Mensagem de erro informando que os dados não constam no banco de dados.  
### Resultado obtido
Mensagem de erro informando que e-mail ou senha estão errados.

![TC 02](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02tc02.png)

##TC03 - Campo e-mail nulo  
### Operação  
Campo e-mail está nulo.  
### Dados Utilizados
E-mail.  
### Resultado esperado
Mensagem de erro informando que o campo está vazio.  
### Resultado obtido
Mensagem de erro pedindo para o usuário preencher o campo.

![TC 03](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02tc03.png)

##TC04 - Campo e-mail em branco  
### Operação  
Campo e-mail está em branco.  
### Dados Utilizados
E-mail.  
### Resultado esperado
Mensagem de erro informando que o campo está em branco.  
### Resultado obtido
Mensagem de erro pedindo para o usuário preencher o campo.  

![TC 04](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02tc03.png)

##TC05 - Campo senha nulo  
### Operação  
Campo senha está nulo.  
### Dados Utilizados
Senha.  
### Resultado esperado
Mensagem de erro informando que o campo está vazio.  
### Resultado obtido
Mensagem de erro pedindo para o usuário preencher o campo.

![TC 05](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02tc05.png)

##TC06 - Campo senha em branco  
### Operação  
Campo senha está em branco.  
### Dados Utilizados
Senha.  
### Resultado esperado
Mensagem de erro informando que o campo está em branco.  
### Resultado obtido
Mensagem de erro pedindo para o usuário preencher o campo.

![TC 06](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02tc05.png)

##TC07 - E-mail cadastrado no sistema, porém a senha está errada  
### Operação  
Preenchimento do campo e-mail válido, porém a senha está errada.  
### Dados Utilizados
E-mail e senha.  
### Resultado esperado
Mensagem de erro informando que a senha está errada.  
### Resultado obtido
Mensagem de erro informando que e-mail ou senha estão errados.

![TC 07](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc02tc02.png)

[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)