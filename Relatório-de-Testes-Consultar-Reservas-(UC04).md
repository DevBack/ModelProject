[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)

#Índice
 
#1. Consultar Reserva
##TC01 - Campo ‘Pesquisar’ vazio
### Operação 
Não preencher o campo 'Pesquisar'.
### Dados Utilizados
Pesquisar.
### Resultado esperado
Listagem de todas as reservas do usuário. 
### Resultado obtido
Todas as reservas do usuário são listadas.

![TC 01](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc04tc01.png)


##TC02 - Campo ‘Pesquisar’ com nome da reserva válido
### Operação 
Campo 'Pesquisar' preenchido com nome de reserva que foi cadastrado em alguma reserva do usuário.
### Dados Utilizados
Pesquisar.
### Resultado esperado
Listagem de todas as reservas que tem o nome da reserva correspondente ao informado pelo usuário. 
### Resultado obtido
Todas as reservas que tem o nome da reserva correspondente ao informado pelo usuário são listadas.

![TC 02](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/uc04tc02.png)

##TC03 - Campo ‘Pesquisar’ com nome da reserva inválido
### Operação 
Campo 'Pesquisar' preenchido com nome de reserva que não foi cadastrado em nenhuma reserva do usuário.
### Dados Utilizados
Pesquisar.
### Resultado esperado
Não haverá listagem de nenhuma reserva.
### Resultado obtido
Nenhuma reserva é listada.

[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)