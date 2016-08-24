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
|24/08/2016 |1.8 |Atualização dos requisitos e correções de vocabulário no documento |Fabíola |

# 1. Introdução
  
Este documento, com relação ao desenvolvimento do projeto SAS (Sistema de Alocação de Salas), tem como objetivo definir o escopo, a proposta, os recursos, o problema a ser resolvido, quem terá acesso ao produto e o tipo de acesso. O objetivo do projeto é criar um sistema que automatize o processo de locação de espaços, salas e laboratórios, da Faculdade do Gama(FGA), atualmente manual, para o cliente, de forma que é esperado que tal sistema auxilie evitando erros e agilizando o processo de locação.

# 2. Posicionamento

## 2.1. Oportunidade de Negócio

No estado atual, a alocação de espaços é feita por cada coordenador da maneira que o mesmo acha mais adequada, por meio do uso de planilhas. Deste modo vários problemas na reserva de espaços acabam ocorrendo, pois para sua alocação cabe a cada coordenador conferir manualmente em sua planilha a disponibilidade do espaço em determinado horário.
Assim, o SAS vêm como solução para automatizar esse processo tornando mais prática e ágil a alocação de espaços, evitando problemas como, por exemplo, reservar um mesmo espaço no mesmo horário para duas atividades distintas e facilitando todo o processo para os coordenadores.

## 2.2. Declaração do Problema

|||
|---|---|
|**O problema de** | Fazer alocação de espaços manualmente com planilhas eletrônicas |
|**Afeta** | Coordenação e corpo acadêmico |
|**Cujo impacto é** | Alocação de espaços a mais ou a menos, choques de horários de espaços, professores e alunos sem poder fazer reservas de maneira simples |
|**Uma boa solução seria** | Um sistema web para alocação de espaços de uso estendido a todos os  interessados|

## 2.3. Declaração da Posição do Produto

|||
|---|---|
|**Para**| Docentes, Discentes e demais membros do Corpo Acadêmico da UnB Gama|
|**Que**| Desejam gerenciar a alocação de espaços com rapidez e eficiência|
|**Sistema de Alocação de  Salas(SAS)**|  É um produto de software|
|**Que**| Um sistema web para alocação de espaços|
|**Diferente**| Do estado atual que requer que o administrador altere manualmente os horários e quem ocupará os espaços|
|**Nosso produto**| Controla as informações relativas aos espaços, seus respectivos horários e sua disponibilidade e permite reservá-las|

# 3. Descrição dos Envolvidos e dos Usuários
## 3.1. Resumo dos Envolvidos
|Nome|Descrição|Responsabilidades|Representantes|
|----|------|---------|------------|
|Cliente |Requisitou o sistema |Fornece os requisitos do sistema |Carla Rocha Aguiar e demais coordenadores dos cursos da FGA|
|Gerentes |Gerenciam o projeto |Elaboram os planos de projeto, Monitoram o andamento do projeto, Revisam o projeto, Auxiliam a equipe de desenvolvimento |Allan Pereira,  Elaine Meirelles, Gustavo Coelho, Jessica Suzuki, Pedro Alcântara|
|Desenvolvedores |Desenvolvem o sistema |Documentação e programação |Fabíola Malta,  Hugo Carvalho, Luis Gustavo, Lucas Oliveira, Vítor Gomes|
|Coachs |Auxiliam os grupos de gerentes e desenvolvedores |Revisam documentos, fornecem treinamentos |Marcelo Ferreira, Dandara Aranha|

## 3.2. Resumo dos Usuários
O sistema possuirá dois tipos de usuários diferentes: Corpo acadêmico e Administrador, como ilustrado na imagem abaixo.


![Imagem 1 - Tipos de Usuários](https://lh6.googleusercontent.com/Q_2gj3fxRTRNhemm0RLlTH0KyUcew9wTzWwdXUOWp_FxGgl5lroAgIExg8iv1-VngXDkgFnaSQ-1o1c=w1920-h971)


|Nome|Descrição|Responsabilidades|Representantes|
|----|------|---------|------------|
|Administrador|Usuário final do sistema |Reserva espaços,Controla reservas |Coordenadores da Faculdade do Gama (FGA)|
|Corpo Acadêmico | Usuário final do sistema|Reserva espaços |Professores, estudantes, técnicos administrativos e demais integrantes do Corpo Acadêmico|
## 3.3. Ambiente do Usuário
* Os clientes utilizam uma planilha eletrônica para gerenciar a utilização e destinação dos espaços.
* A organização de espaços com os horários de professores e matérias é feita pelos clientes de forma não automatizada, portanto suscetível a erros e requerendo muito tempo.
* A secretaria é responsável por mediar reserva de espaços para alunos.
* A reserva efetuada pela secretaria não é digital, sendo anotada em uma planilha física.
* O sistema que será desenvolvido agilizará o processo de alocação de espaços.
* O sistema mudará o processo, que não será feito apenas pela secretaria e pela cliente, possibilitando o acesso para o Corpo Acadêmico.

## 3.4. Principais necessidades dos usuários ou dos envolvidos

A solução utilizada para alocar espaços na Faculdade do Gama é pouco prática, feita em excel e manualmente. Isso permite a existência de choques de horários em espaços e múltiplos espaços reservados pela mesma pessoa e mesmo horário. Além de ser um processo que demanda tempo e ser muito centralizado.

O sistema que será desenvolvido não permite a reserva de um espaço que já está alocado, e permite uma melhor visualização dos espaços, além de permitir maior autonomia dos usuários, que já não dependerão de um intermédio para reservarem uma sala e poderão requisitar a reserva de laboratório.


|Necessidade|Solução Atual|Solução Proposta|
|----|------|---------|
|Alocar espaços para aulas|Tabela no Excel, gerenciada apenas por uma pessoa.|Utilizar um sistema online no qual é possível fazer essa alocação de forma mais segura e rápida.|
|Alocar espaços para outras atividades pertinentes à Universidade|Reservas feitas na secretaria e anotadas em papel|Utilizar o sistema para fazer reserva, eliminando a necessidade do intermédio da secretaria.|


# 4. Visão Geral do Produto

Esta seção expõe uma visão ampla do produto, explicando aspectos gerais de seus recursos.

## 4.1. Perspectiva do Produto

No atual contexto do ambiente acadêmico da Universidade de Brasília, constata-se uma crescente necessidade por um sistema que facilite a alocação de espaços por discentes, docentes e demais integrantes do corpo acadêmico – seja para apresentações de Trabalhos de Conclusão de Curso, aulas de monitoria ou tutoria, dentre outros – visto que, hoje, tal procedimento demanda um longo processo e burocracia. 

## 4.2. Sumário de Capacidades

Tabela 1 – Benefícios do Usuário e Recursos de Suporte

|Benefícios do Usuário|Recursos de Suporte|
|---------------------|-------------------|
|Alocação de espaço feita mais rapidamente.|O processo de análise do pedido, verificando se o espaço no horário requerido está livre, é otimizado.|
|Não há choque de horários (mais de um espaço reservado para a mesma pessoa no mesmo horário ou um espaço reservado para mais de uma pessoa no mesmo horário).|O sistema analisa se o espaço já possui reservas no horário ou se o usuário já possui uma reserva neste horário, impedindo outra reserva.|

## 4.3. Suposições e Dependências

O sistema será utilizado pelo usuário através da internet, logo, há custos de hospedagem. Assim, supõe-se que o cliente arcará com estes valores para que o sistema permaneça online.

## 4.4. Licença e Instalação

Como o sistema estará disponível online, o licenciamento se dá a partir da aceitação dos termos e condições de uso do sistema por parte do usuário. Além disso, não há necessidade de instalação, precisando apenas do acesso a internet e de um navegador web.

# 5. Recursos do Produto
 * **Login no sistema**  
      Login de usuário utilizando informações vinculadas a UnB.   
 * **Visualizar espaços disponíveis**  
      Os usuários pode navegar entre as tabelas de horários para cada espaço.  
 * **Pesquisar espaços**    
      * **Horário**  
            Ambos usuários podem utilizar o filtro de horário para facilitar sua pesquisa.  
      * **Espaços**  
            Ambos usuários podem utilizar de filtro de nome da espaço para facilitar sua pesquisa.  
      * **Status de alocação**  
            Ambos usuários podem utilizar de filtro de status de alocação do espaço para facilitar sua pesquisa.  
 * **Reservar espaço**  
      Os usuários podem requisitar um horário em um espaço.  
 * **Cancelar reserva de espaço**  
      O usuário comum pode cancelar seu pedido de reserva dos espaços anteriormente reservados.  
 * **Controle de reservas**  
      O usuário comum pode visualizar suas reservas vigentes.  
 * **Verificar choque de horários**    
      O administrador pode verificar se uma reserva existe no mesmo horário, no mesmo espaço por requerentes diferentes.  
 * **Ajustar choques de horário**    
      O administrador pode deletar uma reserva que possua algum tipo de choque.  

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
|RF01|O sistema deve permitir que usuário efetue cadastro.|---------|Alta|
|RF02|O sistema deve permitir que o usuário faça login.|---------|Alta|
|RF03|O sistema deve permitir que o usuário consulte os espaços.|---------|Alta|
|RF04|O sistema deve permitir que o usuário reserve espaços.|RF02|Alta|
|RF05|O sistema deve permitir que o corpo acadêmico solicite reserva de laboratório.|RF02|Alta|
|RF06|O sistema deve permitir que o administrador reserve laboratório.|RF03|Alta|
|RF07|O sistema deve permitir que o administrador exclua qualquer reserva.|RF03|Intermediária|
|RF08|O sistema deve permitir o administrador tornar outro usuário administrador.|RF03|Intermediária|
|RF09|O sistema deve permitir que o corpo acadêmico exclua sua própria reserva.|RF03|Intermediária|
|RF10|O sistema deve permitir que o usuário pesquise espaços por disponibilidade|---------|Útil|
|RF11|O sistema deve permitir que o usuário pesquise espaços por horário|---------|Útil|
|RF12|O sistema deve permitir que o usuário pesquise espaços por nome do espaços|---------|Útil|
|RF13|O sistema deve enviar informações da reserva por meio do email do usuário.|---------|Útil|

# 8. Outros Requisitos do Produto
## 8.1 Requisitos do Sistema

* Por ser um sistema web o software necessita de uma conexão estável com a internet para seu funcionamento

## 8.2 Requisitos de Desempenho

* A velocidade da internet tem impacto direto no desempenho da aplicação, sendo necessário uma velocidade suficiente para processar as informações e executar as funcionalidades do sistema
