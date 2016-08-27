# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|28/08/2016|1.0|Criação da estrutura inicial.|Gustavo|

# 1. Introdução

Esse documento tem como finalidade apresentar as políticas do projeto para controle de gerência de configuração e mudança do projeto SAS.

# 2. Gerenciamento de Configuração de Software


## 2.1 Ferramentas

O projeto irá utilizar as seguintes ferramentas e suas versões:

|Ferramenta|Versão|Descrição|
|----------|------|---------|
|Python    |3.5   | Linguagem de programação utilizada no projeto |
|Git       |1.9.1 | Sistema de versionamento de código |
|Django    |1.9.7 | Framework para o desenvolvimento de aplicações web |



### Integração Continua

A integracão continua será realizada pela ferramenta [Travis] (https://travis-ci.org/). Os testes e a cobertura de código pode ser verificada a cada commit submetido para o repositório no GitHub, assim a uma garantia para o projeto do efeitos de alteracões no código. 

## Política de Branches
                                    R1                             R2
Master  |----------------------------|----------------------------- |

Dev        |-------------------------|----------------------------- |

uc1            |----------|      

uc2              |---------------|

uc2_Alan               |-----|

uc2_Hugo           |-----------|

Seguindo o modelo apresentado de baixo para cima: cada desenvolvedor deve ter sua brach caso seja alocado para trabalhar em um caso de uso. Terminado o trabalho, o desenvolvedor deve submeter a branch ao sistema de integracão continúa. Caso todos os testes tenham resultado positivo o desenvolvedor solicita a revisão da branch para um outro desenvolvedor, estando em perfeito estado a branch deve ser mergeda na branch principal do caso de uso. As branches de caso de uso devem ser integradas a branch dev após apresentar resultados posivitos na integracão contínua. Por sua vez a branch dev somente será integrada a master na entegra das releases.

4. Treinamento e Recursos
Para utilizar as ferramentas citadas no item 2.2, serão realizados treinamentos e dojos, de acordo com o cronograma do projeto, visando maior produtividade no desenvolvimento do produto.

