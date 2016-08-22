# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|20/08/2016 |1.0 |Introdução |Lucas |
|20/08/2016 |1.1 |Visão Geral do Produto |Vítor |
|20/08/2016 |1.2 |Recursos do Produto |Hugo |
|20/08/2016 |1.3 |Posicionamento |Luis |
|20/08/2016 |1.4 |Descrição dos Envolvidos e dos Usuários |Fabíola |
|20/08/2016 |1.5 |Revisão da Visão Geral do Produto |Vítor |
|20/08/2016 |1.6 |Requisitos funcionais |Fabíola |
|21/08/2016 |1.7 |Outros Requisitos do Produto e Intervalos de Qualidade |Luis |

# 1. Introdução
  
Este documento, com relação ao desenvolvimento do projeto SAS (Sistema de Alocação de Salas), tem como objetivo definir o escopo, a proposta, os recursos, o problema a ser resolvido, quem terá acesso ao produto e o tipo de acesso. O objetivo do projeto é criar um sistema que automatize o processo de locação de salas, atualmente manual, para o cliente, de forma que é esperado que tal sistema auxilie evitando erros e agilizando o processo de locação.

# 2. Posicionamento

## 2.1. Oportunidade de Negócio

No estado atual, a alocação de salas é feita por cada coordenador da maneira que o mesmo acha mais adequada, através do uso de planilhas. Deste modo vários problemas na reserva de salas acabam ocorrendo, pois para sua alocação cabe a cada coordenador conferir manualmente em sua planilha a disponibilidade da sala em determinado horário.
Assim, o SAS vêm como solução para automatizar esse processo tornando mais prática e ágil a alocação de salas, evitando problemas como, por exemplo, reservar uma mesma sala no mesmo horário para duas atividades distintas e facilitando todo o processo para os coordenadores.

## 2.2. Declaração do Problema

|||
|---|---|
|**O problema de** | Fazer alocação de salas manualmente com planilhas eletrônicas |
|**Afeta** | Coordenação e corpo acadêmico |
|**Cujo impacto é** | Alocação de salas a mais ou a menos, choques de horários de salas, professores e alunos sem poder fazer reservas de maneira simples |
|**Uma boa solução seria** | Um sistema web para alocação de salas de uso estendido a todos os  interessados|

## 2.3. Declaração da Posição do Produto

|||
|---|---|
|**Para**| Docentes, Discentes e demais membros do Corpo Acadêmico da UnB Gama|
|**Que**| Desejam gerenciar a alocação de salas com rapidez e eficiência|
|**Sistema de Alocação de  Salas(SAS)**|  É um produto de software|
|**Que**| Um sistema web para alocação de salas|
|**Diferente**| Do estado atual que requer que o administrador altere manualmente os horários e quem ocupará as salas|
|**Nosso produto**| Controla as informações relativas as salas, seus respectivos horários e sua disponibilidade e permite reservá-las|

# 3. Descrição dos Envolvidos e dos Usuários
## 3.1. Resumo dos Envolvidos
|Nome|Descrição|Responsabilidades|Representantes|
|----|------|---------|------------|
|Cliente |Requisitou o sistema |Fornece os requisitos do sistema |Carla Rocha Aguiar e demais coordenadores dos cursos da FGA|
|Gerentes |Gerenciam o projeto |Elaboram os planos de projeto, Monitoram o andamento do projeto, Revisam o projeto, Auxiliam a equipe de desenvolvimento |Allan Pereira,  Elaine Meirelles, Gustavo Coelho, Jessica Suzuki, Pedro Alcântara|
|Desenvolvedores |Desenvolvem o sistema |Documentação e programação |Fabíola Malta,  Hugo Carvalho, Luis Gustavo, Lucas Oliveira, Vítor Gomes|

## 3.2. Resumo dos Usuários
|Nome|Descrição|Responsabilidades|Representantes|
|----|------|---------|------------|
|Administrador|Usuário final do sistema |Reserva salas,Controla reservas |Coordenadores da Faculdade do Gama (FGA)|
|Usuário | Usuário final do sistema|Reserva salas |Professores, estudantes, técnicos administrativos e demais integrantes do Corpo Acadêmico|
## 3.3. Ambiente do Usuário
* Os clientes utilizam uma planilha eletrônica para gerenciar a utilização e destinação das salas.
* A organização de salas com os horários de professores e matérias é feita pelos clientes de forma não automatizada, portanto suscetível a erros e requerendo muito tempo.
* A secretaria é responsável por mediar reserva de salas e laboratórios para alunos.
* A reserva efetuada pela secretaria não é digital, sendo anotada em uma planilha física.
* O sistema que será desenvolvido agilizará o processo de alocação de salas.
* O sistema mudará o processo, que não será feito apenas pela secretaria e pela cliente, possibilitando o acesso para o Corpo Acadêmico.

## 3.4. Principais necessidades dos usuários ou dos envolvidos

A solução utilizada para alocar salas na Faculdade do Gama é pouco prática, feita em excel e manualmente. Isso permite a existência de choques de horários em salas e múltiplas salas reservadas pela mesma pessoa e mesmo horário. Além de ser um processo que demanda tempo e ser muito centralizado.

O sistema que será desenvolvido não permite a reserva de uma sala que já está alocada, e permite uma melhor visualização das salas, além de permitir maior autonomia dos usuários, que já não dependerão de um intermédio para reservarem uma sala.


|Necessidade|Solução Atual|Solução Proposta|
|----|------|---------|
|Alocar salas para aulas|Tabela no Excel, gerenciada apenas por uma pessoa.|Utilizar um sistema online no qual é possível fazer essa alocação de forma mais segura e rápida.|
|Alocar salas para outras atividades pertinentes à Universidade|Reservas feitas na secretaria e anotadas em papel|Utilizar o sistema para fazer reserva, eliminando a necessidade do intermédio da secretaria.|


# 4. Visão Geral do Produto

Esta seção expõe uma visão ampla do produto, explicando aspectos gerais de seus recursos.

## 4.1. Perspectiva do Produto

No atual contexto do ambiente acadêmico da Universidade de Brasília, constata-se uma crescente necessidade por um sistema que facilite a alocação de salas por discentes, docentes e demais integrantes do corpo acadêmico – seja para apresentações de Trabalhos de Conclusão de Curso, aulas de monitoria ou tutoria, dentre outros – visto que, hoje, tal procedimento demanda um longo processo e burocracia. 

## 4.2. Sumário de Capacidades

Tabela 1 – Benefícios do Usuário e Recursos de Suporte

|Benefícios do Usuário|Recursos de Suporte|
|---------------------|-------------------|
|Alocação da sala feita mais rapidamente.|O processo de análise do pedido, verificando se a sala no horário requerido está livre, é otimizado.|
|Não há choque de horários (mais de uma sala reservada para a mesma pessoa no mesmo horário ou uma sala reservada para mais de uma pessoa no mesmo horário).|O sistema analisa se a sala já possui reservas no horário ou se o usuário já possui uma reserva neste horário, impedindo outra reserva.|

## 4.3. Suposições e Dependências

O sistema será utilizado pelo usuário através da internet, logo, há custos de hospedagem. Assim, supõe-se que o cliente arcará com estes valores para que o sistema permaneça online.

## 4.4. Licença e Instalação

Como o sistema estará disponível online, o licenciamento se dá a partir da aceitação dos termos e condições de uso do sistema por parte do usuário. Além disso, não há necessidade de instalação, precisando apenas do acesso a internet e de um navegador web.

# 5. Recursos do Produto
 * **Login no sistema**  
      Login de usuário utilizando informações vinculadas a UnB.   
 * **Visualizar salas disponíveis**  
      Os usuários pode navegar entre as tabelas de horários para cada sala.  
 * **Pesquisar salas**    
      * **Horário**  
            Ambos usuários podem utilizar o filtro de horário para facilitar sua pesquisa.  
      * **Sala**  
            Ambos usuários podem utilizar de filtro de nome da sala para facilitar sua pesquisa.  
      * **Status de alocação**  
            Ambos usuários podem utilizar de filtro de status de alocação da sala para facilitar sua pesquisa.  
 * **Reservar salas**  
      Os usuários podem requisitar um horário em uma sala.  
 * **Cancelar reserva de salas**  
      O usuário comum pode cancelar seu pedido de reserva das salas anteriormente reservadas.  
 * **Controle de reservas**  
      O usuário comum pode visualizar suas reservas vigentes.  
 * **Verificar choque de horários**    
      O administrador pode verificar se uma reserva existe no mesmo horário, na mesma sala por requerentes diferentes.  
 * **Ajustar choques de horário**    
      O administrador pode editar uma reserva que possua algum tipo de choque.  

## 5.1. Restrições

### 5.1.1. Restrições de implementação

* O sistema deve ser implementado utilização web, na linguagem Python, fazendo uso da framework Django.
* O sistema deve seguir a arquitetura MVC - Model-View-Controller.

### 5.1.2. Restrições do sistema

* O sistema deve ser compatível com a versão 52.0.2743.116 m do Google Chrome.
* O sistema deve ser responsivo, adaptando-se à plataforma que o usuário estiver utilizando.

### 5.1.3. Restrições de confiabilidade

* O sistema deve ter cobertura de erros e exceções - mínimo de 90%;

# 6. Intervalos de Qualidade

* Serão feitas revisões semanalmente com os gerentes de projeto, para que tenha o menor impacto possível no cronograma e, consequentemente, no produto final. Os gerentes de projeto irão avaliar e apontar possíveis pontos a serem melhorados, tendo como base sua experiência e o feedback do cliente, que serão corrigidos pela equipe

# 7. Requisitos
## 7.1. Requisitos Funcionais
|Identificador|Requisito|Depende de|Prioridade|
|---|------|---------|-------|
|RF01|**_O sistema deve permitir que usuário efetue cadastro._****|---------|Alta|
|RF02|O sistema deve permitir que o usuário faça login.|---------|Alta|
|RF03|O sistema deve permitir que o administrador faça login.|---------|Alta|
|RF04|O sistema deve permitir que o usuário consulte as salas.|RF02|Alta|
|RF05|O sistema deve permitir que o usuário reserve sala.|RF02|Alta|
|RF06|O sistema deve permitir que o administrador reserve sala.|RF03|Alta|
|RF07|O sistema deve permitir que o administrador exclua uma reserva.|RF03|Alta|
|RF08|O sistema deve permitir que o administrador consulte as salas.|RF03|Alta|
|RF09|O sistema deve permitir o administrador tornar outro usuário administrador.|RF03|Alta|
|RF10|O sistema deve permitir que o usuário altere sua própria reserva.|RF02|Alta|
|RF11|O sistema deve permitir que o usuário pesquise salas por horário|---------|Alta|
|RF12|O sistema deve permitir que o usuário pesquise salas por nome da sala|---------|Alta|
|RF13|O sistema deve permitir que o usuário pesquise salas por disponibilidade|---------|Alta|

# 8. Outros Requisitos do Produto
## 8.1 Requisitos do Sistema

* Por ser um sistema web o software necessita de uma conexão estável com a internet para seu funcionamento

## 8.2 Requisitos de Desempenho

* A velocidade da internet tem impacto direto no desempenho da aplicação, sendo necessário uma velocidade suficiente para processar as informações e executar as funcionalidades do sistema
