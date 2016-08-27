# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|27/08/2016|1.0|Criação da estrutura inicial.|Gustavo,Pedro|

# 1. Introdução

Esse documento tem como finalidade apresentar as políticas do projeto para controle de gerência de configuração e mudança.

# 2. Gerenciamento de Configuração de Software

## 2.1 Organização, Responsabilidades e Interfaces

A definição de uma política de gerência de configuração e mudança é muito importante para evitar problemas de atrasos acarretando aumentos nos custos do projeto. Portanto, as responsibilidades e atividades abaixo foram definidas para o correto andamento do projeto.

|Atividade|Descrição|Responsável|
|---------|---------|-----------|
Planejar Configuração do Projeto e Controle de Mudanças|Diretrizes para gerenciamento de configuração, políticas e processos para controlar mudanças| Membros GPP
Configurar Ambientes do Projeto|Estabelecer ambiente para criação, manutenção e compartilhamento de repositório do projeto|Equipe de GPP
Alterar e liberar itens de configuração| Criar espaço de trabalho, permitir acesso à artefatos, realizar mudanças nos artefatos e permitir compartilhamento|Equipe de GPP e Equipe de MDS
Gerenciar baselines e releases|	Garantir que o produto de qualidade seja disponibilizado para releases| Equipe de GPP
Monitorar e Relatar Status de Configuração |Realizar a validação do produto, garantir a visibilidade dos artefatos|Equipe de GPP
Gerenciar Solicitações de Mudança |Assegurar que mudanças feitas no projeto sejam consistentes, e que essas mudanças sejam informados a todos da equipe| Equipe de GPP e equipe de MDS 

## 2.2 Ferramentas

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
Master  \----------------------------\----------------------------- \

Dev        \-------------------------\----------------------------- \

uc1            \----------\      

uc2              \---------------\

uc2_Alan               \-----\

uc2_Hugo           \-----------\

Seguindo o modelo apresentado de baixo para cima: cada desenvolvedor deve ter sua brach caso seja alocado para trabalhar em um caso de uso. Terminado o trabalho, o desenvolvedor deve submeter a branch ao sistema de integracão continúa. Caso todos os testes tenham resultado positivo o desenvolvedor solicita a revisão da branch para um outro desenvolvedor, estando em perfeito estado a branch deve ser mergeda na branch principal do caso de uso. As branches de caso de uso devem ser integradas a branch dev após apresentar resultados posivitos na integracão contínua. Por sua vez a branch dev somente será integrada a master na entegra das releases.

4. Treinamento e Recursos
Para utilizar as ferramentas citadas no item 2.2, serão realizados treinamentos e dojos, de acordo com o cronograma do projeto, visando maior produtividade no desenvolvimento do produto.

