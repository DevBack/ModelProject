# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|26/08/2016 |1.0 |Introdução |Vítor |
|26/08/2016 |1.1 | Visão Geral da Visão Lógica |Fabíola |
|27/08/2016 |1.2 | Visão de Casos de Uso |Hugo |

# 1. Introdução

Esta seção apresenta uma visão ampla deste Documento de Arquitetura, apontando sua finalidade e abrangência, bem como definições, acrônimos, abreviações utilizadas dentro do mesmo.

## 1.1. Objetivo

Este documento expõe a arquitetura do Sistema de Alocação de Salas (SAS) de maneira abrangente, pontuando aspectos deste segundo diferentes visões arquiteturais. Além disso, exprime-se decisões significativas adotadas segundo a arquitetura em relação ao sistema.

## 1.2. Escopo

O Documento de Arquitetura descreve o sistema, ajudando na compreensão de seu comportamento, sendo, assim, um meio de avaliar se a abordagem utilizada atende aos requisitos do cliente. Ele tem como base o Documento de Visão e afeta diretamente as ferramentas utilizadas e a implementação do sistema.

## 1.3. Definições, Acrônimos e Abreviações

* MVC: Model-View-Controller (Modelo-Visão-Controladora, em inglês) 
* MTV: Model-Template-View 


# 2. Representação Arquitetural

# 3. Restrições e Metas Arquiteturais

# 4. Visão de Casos de Uso

##4. 1.  **Atores**  

###4. 1. 1. **Usuários**  
Usuário em geral do sistema.  

###4. 1. 2. **Administrador**  
Este ator administra as reservas de sala e usuários administradores.   

###4. 1. 3. **Corpo Docente**  
Este ator realiza atividades (consultar, reservar, cancelar) relativas a reservas.
  
##4. 2. **Diagrama de casos de uso**  
![Imagem - Diagrama de Casos de Uso](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/Casos_de_Uso_v1.jpg)

##4. 3. **Casos de uso**  

###4. 3. 1. **Cadastrar usuário**  
Nesse caso o usuário informa seus dados pessoais para efetuar o cadastro. Este cadastro que é essencial para casos subsequentes.  

###4. 3. 2. **Login do usuário**  
Nesse caso o usuário informa os dados de acesso para logar no sistema. Supoẽ-se que o usuário lembre os dados informados no cadastrado.  

###4. 3. 3. **Login inválido**  
Se o caso 2 falhar por informações incoerentes, o usuário verá na tela mensagem de recusa dos dados e requerirá os dados novamente.  

###4. 3. 4. **Esqueceu a senha**  
Se com o caso 3 o usuário ainda persistir em problemas este caso deverá coletar dados para efetuar a troca da senha.  

###4. 3. 5. **Consulta de espaços**  
Nesse caso o usuário consegue visualizar a lista de espaços.  

###4. 3. 6. **Reserva de espaços**  
Nesse caso o usuário realiza a reserva de qualquer sala, porém apenas requisita um laboratório.

###4. 3. 7. **Excluir reserva de espaços**  
Nesse caso o ator corpo docente apaga a sua reserva feita do espaço. Sendo que o ator adiministrador tem permissões para excluir quaisquer reservas.  

###4. 3. 8. **Tornar usuário Administrador**  
Nesse caso o ator admininstrador seleciona um ator corpo docente para se desempenhar papel de administrador.  

###4. 3. 9. **Pesquisa de reservas**  
Nesse caso o usuário pesquisa espaço utilizando filtros ,sendo eles, disponibilidade,nome,horário dos espaços.  

###4. 3. 10. **Envio de email informativo**  
Nesse caso o sistema envia e-mail pertinente a conta de usuário.  

###4. 3. 11. **Atualiza cadastro**  
Nesse caso o usuário atualiza as informações cadastrais que desejar, sendo informado através de email de suas alterações.  

###4. 3. 12. **Deleta cadastro**  
Nesse caso o usuário deleta sua conta, sendo informado através de email do fim do seu cadastro no sistema.  

###4. 3. 13. **Administrador deleta cadastro**  
Nesse caso o administrador deleta qualquer conta existente no sistema, gerando automaticamente email informativo de fim de cadastro no sistema da conta deletada.  
###4. 3. 14. **Administrador gerência reserva**  
Nesse caso o administrador irá analisar e verificar se aceita ou não pedido de reserva de espaços que feito pelo corpo docente.  
###4. 3. 15.**Mostrar mapa de espaços**  
Nesse caso o usuário verá de forma mapeada a disposição dos espaços, sendo possível acessá-los e conferir informações relativas.  
###4. 3. 16.**Gerar relátorio**  
Nesse caso é gerado um relátorio de utilização do espaço selecionado de acordo com o período e/ou usuários.  

# 5. Visão Lógica

## 5.1. Visão Geral

O sistema será desenvolvido em Django, que possui como padrão de desenvolvimento o MTV(Model-Template-View). Este se enquadra na arquitetura mvc, apresentando de forma análoga a camada template como view e a camada view como a controller.  A imagem abaixo explicita as camadas e como elas se relacionam. Em vermelho estão destacados os nomes da arquitetura MVC.

![Imagem - Visão Geral](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/arquitetura1.png)
## 5.2. Pacotes de Design Significativos do Ponto de Vista da Arquitetura

## 5.3. Realizações de Casos de Uso

# 6. Visão de Processos

# 7. Visualização da Implementação

# 8. Visão da Implementação

## 8.1. Visão Geral

## 8.2. Camadas

# 9. Tamanho e Desempenho

# 10. Qualidade