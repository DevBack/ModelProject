# Histórico de revisões deste documento

|Data      |Versão|Descrição            |Autor    |
|----------|------|---------------------|---------|
|02/09/2016|1.0   |Criação do documento: estrutura inicial |Allan    |
|05/09/2016|1.1   |Adicionado conteúdo em todo documento   |Allan    |
|14/09/2016|1.2   |Revisão na aplicabilidade e uso das métricas e ferramentas.   |Allan    |
|14/09/2016|1.3   |Alterando explicação em relação ao flake 8 e usabilidade  |Jessica      |
|20/09/2016|1.4   |Adicionado justificativa para escolha das métricas  |Allan      |
|20/09/2016|1.5   |Adicionado link para acompanhamento do plano  |Allan      |

# 1. Introdução
Este documento descreve os procedimentos gerenciais que visam estabelecer, controlar, assegurar e validar padrões de qualidade do produto em desenvolvimento.

# 2. Planejamento
## 2.1. Métricas de Qualidade
Será feito o uso de três métricas de qualidade de código: 

 1. Cobertura de Testes;

 2. Complexidade Ciclomática;

 3. Churn: Alterações de arquivo;

O acompanhamento dos valores das métricas será realizado com auxílio das ferramentas discutidas em [5. Ferramentas Utilizadas](#5-ferramentas-utilizadas). As métricas são coletadas a partir da branch dev, exceto cobertura de testes que é observada em qualquer branch. A coleta é realizada após a finalização de cada funcionalidade (Caso de Uso/História de Usuário) e serão utilizadas para avaliar a necessidade de refatoração, conforme deliberado em cada métrica e possivelmente apontar vícios de programação, de forma que a equipe de gerência pode sugerir melhorias antes da codificação de novas funcionalidades e antes de disponibilizar o código na branch master.

### 2.1.1. Cobertura de Testes
É estabelecido que o o projeto deverá ter cobertura de código de, no mínimo, 90%, logo é obrigatório a definição desta métrica. Este acompanhamento será feito através da ferramenta Coveralls. Esta ferramenta computa automaticamente a cobertura de código com base nos arquivos de teste do repositório.

#### 2.1.1.1. Indicadores

|Percentual          |Descrição            |
|--------------------|---------------------|
| < 90% de cobertura | Insuficiente        |
| 90% de cobertura   | Aceitável           |
| > 90% de cobertura | Ótimo               |


### 2.1.2. Complexidade Ciclomática

Esta métrica avalia a quantidade de caminhos de execução independentes a partir de um código fonte. Ela foi escolhida em virtude do caráter delicado que o projeto apresenta ao correlacionar informações de reservas em locais e horários. A abordagem de codificação do software que tratará estas informações pode se tornar dependiosa e consequentemente gerar complexidade computacional custosa podendo refletir em tempo de espera em consultas. 
A complexidade ciclomática será avaliada como métrica através da engine Rudon do Code Climate. O Flake8 fornece uma visualização prévia em tempo de desenvolvimento sobre vícios anti-patterns que possam impactar nesta métrica de forma que será necessário utilizar o Flake 8 ao final de cada caso de uso, antes de fazer o merge. O Code Climate vem como complemento validador, é através dele que é avaliada a necessidade de refatoração, conforme indicadores:

#### 2.1.2.1. Indicadores

|Valor (File Rating) |Descrição            |
|--------------------|---------------------|
|C, D, F             |Insuficiente         |
|B                   |Aceitável            |
|A                   |Ótimo                |


### 2.1.3. Churn: Alterações de arquivo

Esta métrica diz respeito ao número de vezes que um arquivo foi alterado nos últimos 90 dias. Através dela a equipe de gerenciamento se encarrega de identificar pontos do projeto que estão demandando maior trabalho da equipe utilizando como base os arquivos que mudam mais frequentemente avaliando quais são as suas qualidades relativas, em outras palavras, esta métrica fornece base técnica para avaliação empírica do direcionamento de esforços no projeto. 

Tal métrica é útil para avaliar fragilidades de especificações que podem estar gerando valores altos para esta métrica. Logo ela serve como base para a equipe decidir sobre refatorações em especificações, especialmente arquiteturais.


#### 2.1.3.1. Indicadores

|Valor (Cor do ponto no gráfico)|Descrição            |
|-------------------------------|---------------------|
|Vermelho, laranja              |Insuficiente: Avaliar obrigatoriamente |
|Amarelo                        |Aceitável: Avaliar de acordo com disponibilidade de tempo no cronograma|
|Verde                          |Ótimo: Aceitar.                |

A imagem abaixo exemplifica como são obtidos resultados desta métrica:

![Churn](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/churn.png) 

## 2.2. Critérios de Qualidade

### 2.2.1. Qualidade de código
O [PEP8 - Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) estabelece padrões de codificação que devem ser utilizados na implementação do software. A partir do PEP8 foi desenvolvido a [Folha de estilo](https://github.com/fga-gpp-mds/2016.2-Time05/wiki/Folha-de-Estilo) que visa aplicar uniformidade na escrita de código buscando melhorar a qualidade do mesmo em termos de legibilidade e manutenabilidade. Nela constam parâmetros tais como espaçamentos, linhas em branco, nomes de funções, variáveis e afins, e pequenas técnicas simplistas que visam impactar em um código mais eficaz através da identificação de anti-patterns.

### 2.2.2. Integração Contínua
É uma prática de integração frequente das diversas partes de código de forma a evitar precocemente diversos problemas que possam surgir em uma integração de código tardia.
O desenvolvimento do projeto contará com auxílio da ferramenta Travis CI para integração contínua de código.

O Travis aprsenta um dashboard com todas as builds feitas. As builds são feitas toda vez que há um novo commit no repositório do projeto. 

### 2.2.3. Usabilidade
O framework Bootstrap será utilizado visando melhorar a experiência de usuário e implementar responsividade nas telas do sistema. Serão feitos protótipos de alta fidelidade e validados com o cliente antes da construção da interface, para que as mesmas sigam o protótipo aprovado pelo cliente.

## 2.3. Ferramentas Utilizadas
* [Travis CI](https://travis-ci.org/fga-gpp-mds/2016.2-SAS_FGA) - Integração contínua.
* [Flake8](https://pypi.python.org/pypi/flake8/) - Adequação a folha de estilo; Análise estática; Prevenção de impacto em Complexidade Ciclomática.
* [Coveralls](https://coveralls.io/) - Contabilidade de cobertura de testes.
* [Selenium](http://www.seleniumhq.org/) - Testes de aceitação automatizados.
* [Code Climate](https://www.codeclimate.com) - Avaliação das métricas de complexidade ciclomática e Churn.
* [Bootstrap](http://getbootstrap.com/) - Framework para implementação de interface de usuário responsiva e melhoria da experiência de usuário como um todo.
* [JustinMind] (http://www.justinmind.com/) - Ferramente para criação de protótipos de alta fidelidade

# 3. Monitoramento e Controle da Qualidade
* *Documentação*: Todos os membros da equipe de gerência de projeto deverão realizar uma leitura minuciosa dos planos de gerenciamento após tais serem elaborados, de forma a elucidar eventuais falhas ou melhorias aplicáveis. Na reunião semanal deverá ser abordado tal assunto.

* *Métricas*: Ao final de cada iteração da fases de construção e transição realizar a coleta das métricas estabelecidas e avaliar se os padrões de qualidade estão sendo atendidos. Caso não estejam, a equipe deverá tentar alocar tempo para refatoração do código de acordo com os indicadores das métricas.

* *Folha de estilo*: Ao final de cada caso de uso, um desenvolvedor deverá fazer uso da ferramenta Flake8 para checar eventuais incoerências com a folha de estilo identificadas durante o desenvolvimento. Dessa forma, a integração do novo código será aceita somente após a validação com o Flake8.

* *Usabilidade*: Os desenvolvedores deverão se ater previamente a responsividade das telas, conforme requisito não funcional de usabilidade especificado. Ao final de cada iteração serão realizadas rotinas de verificação de responsividade das telas e facilidade de uso.

O monitoramento da qualidade é registrado em: [Acompanhamento da Qualidade](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Acompanhamento-Métricas-de-Qualidade)