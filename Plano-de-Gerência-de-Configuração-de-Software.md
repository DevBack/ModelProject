# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|27/08/2016|1.0|Criação da estrutura inicial.|Gustavo e Pedro|
|28/08/2016|1.1|Adição da imagem de política de branches.|Gustavo|
|03/09/2016|1.2|Adição da politica de GCS para o escopo do projeto|Pedro|
|04/09/2016|1.3|Revisão ortográfica do documento|Elaine|

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

O projeto irá utilizar as seguintes ferramentas - que compõe o ambiente de desenvolvimento - e suas versões:

|Ferramenta|Versão|Descrição|
|----------|------|---------|
|Python    |3.5   | Linguagem de programação utilizada no projeto |
|Git       |1.9.1 | Sistema de versionamento de código |
|Django    |1.9.7 | Framework para o desenvolvimento de aplicações web |
|GitHub    | - | Ferramenta paro gerenciamento de documentos e código|



### Integração Contínua

A integracão contínua será realizada através da ferramenta [Travis] (https://travis-ci.org/). Os testes e a cobertura de código podem ser verificados a cada commit submetido para o repositório no GitHub, assim, há uma garantia para o projeto dos efeitos de alterações no código.

## 2.3 Níveis de controle de configuração 

O projeto irá utilizar três níveis de controle de configuração, sendo eles:

|Nível|Descrição|
|-----|-------|
|Controlado|A mudança somente será feita após a aprovação do grupo de GPP|
|Monitorada|A mudança somente será feita a partir de uma política estabelecida para a configuração|
|Comunicada|A alteração pode ser feita por qualquer membro do grupo mediante a comunicação para os outros integrantes|

## 2.3.1 Definição de nível para as configurações

|Configuração|Nível|
|------------|-----|
|Documentação do Projeto|Comunicada|
|Código|Monitorada|
|Ambiente de desenvolvimento e Escopo do Projeto|Controlado|

## 2.3.2 Política de Monitoramento de Código

O monitoramento de mudança de código será feito a partir da seguinte política de branches:

![Imagem 1 - Política de Branches](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/politicadebranches.png "Imagem 1 - Política de Branches")

Seguindo o modelo apresentado de baixo para cima: cada desenvolvedor deve ter sua branch caso seja alocado para trabalhar em um caso de uso. Terminado o trabalho, o mesmo deve submeter a branch ao sistema de integracão contínua. Caso todos os testes tenham resultado positivo, o desenvolvedor solicita a revisão da branch para um outro desenvolvedor. Estando em perfeito estado, a branch deve ser acoplada à branch principal do caso de uso. As branches de caso de uso devem ser integradas à branch _dev_, após apresentar resultados posivitos na integracão contínua. Por sua vez a branch _dev_ somente será integrada a _master_ na entrega das releases.

## 2.3.2 Política de Controle do Escopo do Projeto
As mudanças no escopo do projeto devem obedecer as diretrizes estabelecidas no pano de [Gerenciamento de Escopo](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Gerenciamento-de-Escopo) (item 2.5.).

# 3. Treinamento e Recursos
Para utilizar as ferramentas citadas no item 2.2, serão realizados treinamentos e dojos, de acordo com o cronograma do projeto, visando maior produtividade no desenvolvimento do produto.

