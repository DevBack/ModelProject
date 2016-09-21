[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)

#1. Criar Reserva  

##TC 01 - Todos os campos válidos  
###Operação  
Informar todos os dados necessários corretamente.  
###Dados utilizados
Nome da reserva, Hora Inicial, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de confirmação da reserva.  
###Resultado obtido  
Página de confirmação da reserva. 
    
##TC 02 - Todos os campos inválidos  
###Operação  
Informar todos os dados necessários incorretamente.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando erro.  
###Resultado obtido  
Página de criação da reserva com mensagem erros nos campos.  
  
##TC 03 - Campo 'Nome da Reserva' nulo  
###Operação  
Informar todos os dados necessários corretamente, e Nome da Reserva nulo.  
###Dados utilizados  
Hora Inicial, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência do elemento nome.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência do elemento nome.  

![TC 03](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/nomeReservaNulo.png)
 
##TC 04 - Campo 'Nome da Reserva' vazio  
###Operação  
Informar todos os dados necessários corretamente, e Nome da Reserva vazio.  
###Dados utilizados  
Hora Inicial, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência de elementos para nome.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência de elementos de nome.  
  
##TC 05 - Campo 'Hora inicial' nulo  
###Operação  
Informar todos os dados necessários corretamente, e Hora Inicial nula.  
###Dados utilizados  
Nome da reserva, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência do elemento Hora Inicial.
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência do elemento Hora Inicial.  

![TC 05](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/horaInicialNulo.png)  

##TC 06 - Campo 'Hora inicial' vazio  
###Operação  
Informar todos os dados necessários corretamente, e Hora Inicial vazia.  
###Dados utilizados  
Nome da reserva, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência de elementos em Hora Inicial.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência de elementos na Hora Inicial.  
  
##TC 07 - Campo 'Hora inicial' inválido  
###Operação  
Informar todos os dados necessários corretamente, exceto Hora Inicial.  
###Dados utilizados  
Nome da reserva, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando que Hora Inicial não segue formato válido.  
###Resultado obtido  
Apresenta-se o seguinte erro
     
![TC 07](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/erroHoraInicial.png)
 
##TC 08 - Campo 'Hora Final' nulo  
###Operação  
Informar todos os dados necessários corretamente, e Hora Final nula.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência do elemento Hora Final.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência do elemento Hora Final.  

![TC 08](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/horaFinalNulo.png)
  
##TC 09 - Campo 'Hora Final' vazio  
###Operação  
Informar todos os dados necessários corretamente, e Hora Final vazia.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência de elementos na Hora Final.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência de elementos na Hora Final.  
  
##TC 10 - Campo 'Hora Final' inválido  
###Operação  
Informar todos os dados necessários corretamente, exceto Hora Final.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final, Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando Hora Final inválido.  
###Resultado obtido  
Apresenta erro semelhante ao [TC 07].

##TC 11 - Campo 'Data Inicial' nulo  
###Operação  
Informar todos os dados necessários corretamente, e Data Inicial nula.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência do elemento Data Inicial.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência do elemento Data Inicial.  
![TC 11](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/dataInicialNulo.png)
  
##TC 12 - Campo 'Data Inicial' vazia
###Operação  
Informar todos os dados necessários corretamente, e Data Inicial vazia.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência de elementos de Data inicial.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência de elementos de Data Inicial.  
  
##TC 13 - Campo 'Data Inicial' inválido  
###Operação  
Informar todos os dados necessários corretamente, exceto Data Inicial.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final,Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando Data inicial no formato inválido.  
###Resultado obtido  
Apresenta erro semelhante ao [TC 07]
    
##TC 13 - Campo 'Data Final' nulo  
###Operação  
Informar todos os dados necessários corretamente, e Data Final nula.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final, Data Inicial, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência do elemento Data Final.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência do elemento Data Final.  

![TC 13](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/dataFinalNulo.png)
  
##TC 14 - Campo 'Data Final' vazia  
###Operação  
Informar todos os dados necessários corretamente, e Data Final vazia.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final, Data Inicial, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando ausência de elementos de Data Final.  
###Resultado obtido  
Página de criação da reserva com mensagem indicando ausência de elementos de Data Final.  
  
##TC 15 - Campo 'Data Final' inválido  
###Operação  
Informar todos os dados necessários corretamente, exceto Data Final.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final,Data Inicial, Data Final, Espaço, Prédio, Dias da semana.  
###Resultado esperado  
Visualização da página de criação da reserva com mensagem indicando Data Final no formato inválido.  
###Resultado obtido  
Apresenta erro semelhante co [TC 07]

##TC 16 - Campo 'Dia da Semana' nulo  
###Operação  
Informar todos os dados necessários corretamente, e nenhuma opção selecionada de Dia da Semana.  
###Dados utilizados  
Nome da reserva, Hora Inicial, Hora Final,Data Inicial, Data Final, Espaço, Prédio.  
###Resultado esperado  Visualização da página de criação da reserva com mensagem indicando que nenhum dia da semana foi selecionado.  
###Resultado obtido  
Página de visualização indicando necessidade de informar o campo.  

![TC 16](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/diasDaSemana.png)
  
[retornar para Relatório de Testes](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Relat%C3%B3rio-de-Testes)