# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|26/08/2016 |1.0 | Introdução |Vítor |
|26/08/2016 |1.1 | Visão Geral da Visão Lógica |Fabíola |
|27/08/2016 |1.2 | Visão de Casos de Uso |Hugo |
|27/08/2016 |1.3 | Qualidade |Vítor |
|27/08/2016 |1.4 | Atualizando Visão de Casos de Uso |Hugo |
|28/08/2016 |1.5 | Atualizando Visão Lógica|Fabíola |
|30/08/2016 |1.6 | Representação Arquitetural |Lucas |
# 1. Introdução

Esta seção apresenta uma visão ampla deste Documento de Arquitetura, apontando sua finalidade e abrangência, bem como definições, acrônimos, abreviações utilizadas dentro do mesmo.

## 1.1. Objetivo

Este documento expõe a arquitetura do Sistema de Alocação de Salas (SAS) de maneira abrangente, pontuando aspectos deste segundo diferentes visões arquiteturais. Além disso, exprime-se decisões significativas adotadas segundo a arquitetura em relação ao sistema.

## 1.2. Escopo

O Documento de Arquitetura descreve o sistema, ajudando na compreensão de seu comportamento, sendo, assim, um meio de avaliar se a abordagem utilizada atende aos requisitos do cliente. Ele tem como base o Documento de Visão e afeta diretamente as ferramentas utilizadas e a implementação do sistema.

## 1.3. Definições, Acrônimos e Abreviações

* MVC: Model-View-Controller (Modelo-Visão-Controladora, em inglês) 
* MTV: Model-Template-View (Modelo-Template-Visão, em inglês)


# 2. Representação Arquitetural

A arquitetura utilizada será a arquitetura do django que tem como padrão a mvc(figura 1). A camada de modelo(model) é responsável pelas classes de domínio, pela leitura e escrita de dados e pela comunicação com o banco de dados. A camada de visão(View) é responsável pela interface com o usuário, ou seja, é ela que faz a apresentação da aplicação. E a camada de controle(controller) é responsável por trabalhar com as requisições e fazer o controle em si da aplicação.

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
![Imagem - Diagrama de Casos de Uso](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/use_cases_v2.jpg)

# 5. Visão Lógica

## 5.1. Visão Geral

O sistema será desenvolvido em Django, que possui como padrão de desenvolvimento o MTV(Model-Template-View). Este se enquadra na arquitetura MVC, de acordo com o "The Django Book". Porém, a arquitetura implementada no django possui algumas singularidades. Abaixo está uma imagem das camadas da arquitetura utilizada no django e como elas se relacionam.

![Imagem - Visão Geral](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/arquitetura1.png)
## 5.2. Pacotes de Design Significativos do Ponto de Vista da Arquitetura

Os pacotes de design signficativos são: model, template e view.
* model: faz interface com o banco de dados, é responsável por leitura, validação e escrita de dados.
* view: contém a camada lógica do sistema.
* template: faz interface com o usuário, contém as páginas HTML.

# 6. Visualização da Implementação

# 7. Visão da Implementação

## 7.1. Visão Geral

## 7.2. Camadas

# 8. Tamanho e Desempenho

# 9. Qualidade

A arquitetura utilizada no sistema afeta diretamente sua capacidade de manutenção, facilitando-a, já que sua implementação estará devidamente organizada. Além disso, como o MVC é um padrão de arquitetura amplamente utilizado, há efeitos práticos em sua confiabilidade.

# 10. Referências

* [The Django Book](http://www.djangobook.com/en/2.0/). Acesso em 28/08/2016.