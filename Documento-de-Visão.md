# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|20/08/2016 |1.0 |Introdução |Lucas |
|20/08/2016 |1.1 |Visão Geral do Produto |Vítor |
|20/08/2016 |1.2 |Recursos do Produto |Hugo |
|20/08/2016 |1.3 |Posicionamento |Luis |
|20/08/2016 |1.4 |Descrição dos Envolvidos e dos Usuários |Fabíola |
|20/08/2016 |1.5 |Revisão da Visão Geral do Produto |Vítor |
|20/08/2016 |1.6 |Restrições |Vítor |
|20/08/2016 |1.7 |Requisitos funcionais |Fabíola |
|21/08/2016 |1.8 |Outros Requisitos do Produto e Intervalos de Qualidade |Luis |
|24/08/2016 |1.9 |Atualização dos requisitos e correções de vocabulário no documento |Fabíola |
|24/08/2016 |2.0 |Atualização dos requisitos |Lucas |
|24/08/2016 |2.1 |Regras de negócio |Lucas |
|24/08/2016 |2.2 |Atualização dos requisitos e tipos de dependência |Luis |
|24/08/2016 |2.3 |Especificações Suplementares |Luis |
|25/08/2016 |2.4 |Atualização da Descrição dos Envolvidos e dos Usuários |Fabíola |
|25/08/2016 |2.5 |Atualização dos Recursos do Produto|Lucas |
|25/08/2016 |2.6 |Atualização do Ambiente do Usuário e Descrição dos Envolvidos |Hugo |
|25/08/2016 |2.7 |Atualização da Perspectiva do produto, Posicionamento e exclusão das Suposições e Dependências e Licença e Instalação |Luis |
|26/08/2016 |2.8 |Atualização de Especificações Suplementares para Requisitos Não-Funcionais, atualização de Regras de Negócio e Restrições, reinclusão e atualização de Suposições e Dependências |Vítor |
|26/08/2016 |2.9 |Atualização dos requisitos e das regras de negócio |Lucas|
|27/08/2016 |3.0 |Atualização dos requistos, das regras de negócio e das descrição do usuário |Lucas e Fabíola |

# Índice

[1. Introdução](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#1-introdu%C3%A7%C3%A3o)

[2. Posicionamento](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#2-posicionamento)

[3. Descrição dos Envolvidos e dos Usuários](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#3-descri%C3%A7%C3%A3o-dos-envolvidos-e-dos-usu%C3%A1rios)

[4. Visão Geral do Produto](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#4-vis%C3%A3o-geral-do-produto)

[5. Recursos do Produto](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#5-recursos-do-produto)

[6. Restrições](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#6-restri%C3%A7%C3%B5es)

[7. Requisitos](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Documento-de-Vis%C3%A3o#7-requisitos)


# 1. Introdução
  
Este documento, com relação ao desenvolvimento do projeto SAS (Sistema de Alocação de Salas), tem como objetivo definir o escopo, a proposta, os recursos, o problema a ser resolvido, quem terá acesso ao produto e o tipo de acesso. O objetivo do projeto é criar um sistema que automatize o processo de locação de espaços, salas e laboratórios, da Faculdade do Gama (FGA), atualmente manual, para o cliente, de forma que é esperado que tal sistema auxilie evitando erros e agilizando o processo de locação.

# 2. Posicionamento

## 2.1. Oportunidade de Negócio

No estado atual, a alocação de espaços é feita por cada coordenador da maneira que o mesmo acha mais adequada, por meio do uso de planilhas. Deste modo, vários problemas na reserva de espaços acabam ocorrendo, pois para sua alocação cabe a cada coordenador conferir manualmente em sua planilha a disponibilidade do espaço em determinado horário.
Assim, o SAS vem como solução para automatizar esse processo tornando mais prática e ágil a alocação de espaços, evitando problemas como, por exemplo, reservar um mesmo espaço no mesmo horário para duas atividades distintas e facilitando todo o processo para os coordenadores.

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
|**Sistema de Alocação de  Salas**|  É um sistema web|
|**Que**| Automatizará e facilitará a alocação de espaços|
|**Diferente**| Do Sistema de Alocação de Salas da Universidade Federal de São Carlos|
|**Nosso produto**| Controla as informações relativas a todos os espaços, sua disponibilidade e permite reservá-las, para qualquer horário|

# 3. Descrição dos Envolvidos e dos Usuários
## 3.1. Descrição dos Envolvidos
|Nome|Descrição|Responsabilidades|Critério de Sucesso|Representantes|
|----|------|---------|------------|------------|
|Cliente |Requisitou o sistema |Fornece e valida os requisitos do sistema, avalia o andamento do produto a cada release. | Receber um sistema funcional que responda ao requisitado |Carla Rocha Aguiar|
|Gerentes |Gerenciam o projeto |Elaboram os planos de projeto, Monitoram o andamento do projeto, Revisam o projeto, Auxiliam a equipe de desenvolvimento |Conseguir gerenciar a equipe de forma a entregar o produto dentro do prazo proposto |Allan Pereira,  Elaine Meirelles, Gustavo Coelho, Jessica Suzuki, Pedro Alcântara|
|Desenvolvedores |Desenvolvem o sistema |Documentação e programação |Conseguir desenvolver o produto proposto|Fabíola Malta,  Hugo Carvalho, Luis Gustavo, Lucas Oliveira, Vítor Gomes|
|Coachs |Auxiliam os grupos de gerentes e desenvolvedores |Revisam documentos, fornecem treinamentos |Observar que o produto tenha sido desenvolvido dentro dos critérios propostos pelas matérias|Marcelo Ferreira, Dandara Aranha|

## 3.2. Descrição dos Usuários
O sistema possuirá dois tipos de usuários diferentes: Corpo acadêmico e Administrador, como ilustrado na imagem abaixo.

![Imagem 1 - Tipos de Usuários](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/imagemUsuarios.png "Imagem 1 - Tipos de Usuários")


|Nome|Descrição|Responsabilidades|Critérios de Sucesso|Representantes|
|----|------|---------|------------|------------|
|Administrador|Usuário final do sistema |Reserva espaços,Controla reservas|Conseguir gerenciar reserva de espaços |Coordenadores da Faculdade do Gama (FGA)|
|Corpo Acadêmico | Usuário final do sistema|Reserva espaços |Conseguir reservar espaços|Professores, estudantes, técnicos administrativos e demais integrantes do Corpo Acadêmico|
## 3.3. Ambiente do Usuário
O sistema deve propiciar, através da intenet, acesso simultâneo e a qualquer horário. E realizará comunicações pertinentes ao usuário através de e-mails. Pressupõe-se assim, que o usuário tenha acesso a internet para utilizar da plataforma, sendo necessário que os dispositivos possuam no mínimo um browser para navegação. Com isso, a velocidade de conexão pode interferir na experiência do usuário final.  

## 3.4. Principais necessidades dos usuários ou dos envolvidos

A solução utilizada para alocar espaços na Faculdade do Gama é pouco prática, feita em excel e manualmente. Isso permite a existência de choques de horários em espaços e múltiplos espaços reservados pela mesma pessoa e mesmo horário. Além de ser um processo que demanda tempo e ser muito centralizado.


|Necessidade|Solução Atual|Solução Proposta|
|----|------|---------|
|Alocar espaços para aulas|Tabela no Excel, gerenciada apenas por uma pessoa.|Utilizar um sistema online no qual é possível fazer essa alocação de forma mais segura e rápida.|
|Alocar espaços para outras atividades pertinentes à Universidade|Reservas feitas na secretaria e anotadas em papel|Utilizar o sistema para fazer reserva, eliminando a necessidade do intermédio da secretaria.|


# 4. Visão Geral do Produto

Esta seção expõe uma visão ampla do produto, explicando aspectos gerais de seus recursos.

## 4.1. Perspectiva do Produto

No atual contexto do ambiente acadêmico da Universidade de Brasília, constata-se uma crescente necessidade por um sistema que facilite a alocação de espaços por discentes, docentes e demais integrantes do corpo acadêmico – seja para apresentações de Trabalhos de Conclusão de Curso, aulas de monitoria ou tutoria, dentre outros – visto que, hoje, tal procedimento demanda um longo processo e burocracia. 

Existem softwares semelhantes ao sistema do nosso projeto, como, por exemplo, o Sistema de Alocação de Salas da Universidade Federal de São Carlos. Ambos tem como objetivo geral, de forma simplificada, automatizar e facilitar a alocação de espaços dentro de sua respectiva universidade. Porém, nosso sistema pretende ser mais abrangente e dará mais autonomia ao corpo acadêmico, visto que permitirá uma melhor visualização dos espaços, abrangerá todos espaços da faculdade, ao contrário do Sistema de Alocação de Salas da Universidade Federal de São Carlos, que serve apenas para salas de informática. E o corpo acadêmico não dependerá da confirmação do administrador para a alocação de um espaço, caso o espaço esteja vago ele será automaticamente reservado, salvo para os laboratórios e o anfiteatro, que dependerão da permissão do administrador.


## 4.2. Sumário de Capacidades  

|Benefícios do Usuário|Recursos de Suporte|
|---------------------|-------------------|
|Alocação de espaço feita mais rapidamente.|O processo de análise do pedido, verificando se o espaço no horário requerido está livre, é otimizado.|
|Não há choque de horários (mais de um espaço reservado para a mesma pessoa no mesmo horário ou um espaço reservado para mais de uma pessoa no mesmo horário).|O sistema analisa se o espaço já possui reservas no horário ou se o usuário já possui uma reserva neste horário, impedindo outra reserva.|

## 4.3. Suposições e Dependências

* O cliente deverá arcar com todas as despesas relativas à manutenção e disponibilidade do sistema.

# 5. Recursos do Produto
 * **Cadastrar no sistema**  
      O Usuário pode se cadastrar no sistema para utilizar o serviço.
 * **Atualizar dados no sistema**  
      O Usuário pode atualizar seus dados cadastrados.
 * **Retirar reserva**  
      O Usuário pode retirar reservas anteriormente efetuadas.
 * **Login no sistema**  
      Login de Usuário utilizando informações vinculadas a UnB.   
 * **Visualizar espaços disponíveis**  
      O Usuário pode navegar entre as tabelas de horários para cada espaço.
 * **Pesquisar espaços**    
      O Usuário pode pesquisar espaços na Faculdade, utilizando filtros de horário ou de locação disponível, se desejar.
 * **Reservar espaço**  
      O Usuário podem requisitar um horário em um espaço.  
 * **Controle de reservas**  
      O Usuário pode visualizar as reservas vigentes.  
 * **Verificar choque de horários**    
      O Administrador pode verificar se uma reserva existe no mesmo horário, no mesmo espaço por requerentes diferentes.  
 * **Ajustar choques de horário**    
      O Administrador pode deletar uma reserva que possua algum tipo de choque.  

# 6. Restrições

## 6.1 Restrições de implementação

* O sistema deve ser implementado utilização web, na linguagem Python, fazendo uso da framework Django.

## 6.2 Restrições de confiabilidade

* O sistema deve ter cobertura de testes - mínimo de 90%;

# 7. Requisitos
## 7.1. Requisitos Funcionais

| | |
|---|---|
|**Alta** | Requisitos indispensáveis para o funcionamento do sistema |
|**Intermediária** | Requisitos importantes para o sistema, mas caso não sejam implementados não resultará em um mal funcionamento do sistema |
|**Útil** | Requisitos que não são usados com tanta frequência e não são tão significativos na satisfação que o usuário tem sobre o sistema |

|Identificador|Requisito|Depende de|Prioridade|
|---|------|---------|-------|
|RF01|O sistema deve permitir que Usuário efetue cadastro.|---------|Alta|
|RF02|O sistema deve permitir que o Usuário faça login.|RF01|Alta|
|RF03|O sistema deve permitir que o Usuário consulte os espaços.|RF02|Alta|
|RF04|O sistema deve permitir que o Usuário reserve espaços.|RF03|Alta|
|RF05|O sistema deve permitir que o Usuário exclua reserva.|RF04|Intermediária|
|RF06|O sistema deve permitir o Administrador tornar outro Usuário Administrador.|RF02|Intermediária|
|RF07|O sistema deve permitir que o Usuário pesquise espaços por disponibilidade.|RF03|Útil|
|RF08|O sistema deve permitir que o Usuário pesquise espaços por horário.|RF03|Útil|
|RF09|O sistema deve permitir que o Usuário pesquise espaços por nome do espaços.|RF03|Útil|
|RF10|O sistema deve enviar informações da reserva ao email cadastrado do Usuário.|RF01|Útil|
|RF11|O sistema deve permitir que o Usuário atualize seu cadastro.|RF02|Intermediária|
|RF12|O sistema deve permitir que o Usuário delete seu cadastro.|RF02|Intermediária|
|RF13|O sistema deve permitir que o Administrador delete o cadastro de qualquer Usuário.|RF02|Intermediária|
|RF14|O sistema deve mostrar um mapa de localização dos espaços.|RF02|Alta|
|RF15|O sistema deve gerar relatório de utilização de determinado espaço por período.|RF03|Útil|
|RF16|O sistema deve gerar relatório de utilização de espaços por Usuário.|RF02|Útil|
|RF17|O sistema deve permitir que o usuário liste suas reservas.|RF04|Intermediária|
|RF18|O sistema deve permitir que o usuário consulte suas reservas.|RF17|Intermediária|
|RF19|O sistema deve permitir que o usuário visualize a página de perguntas frequentes.|--------|Útil|

## 7.2 Regras de Negócio

|Identificador|Requisito Funcional|Restrição|
|---|------|------|
|RN01|RF04|A reserva de Laboratórios necessita ser confirmada mediante autorização do Administrador.|
|RN02|RF04|O Administrador gerenciará o período de reservas.|
|RN03|RF05|Corpo Acadêmico somente pode excluir suas próprias reservas.|
|RN04|RF05|Administrador pode excluir qualquer reserva.|
|RN05|RF10|O sistema enviará email quando houver qualquer modificação na reserva ou na solicitação de reserva.|
|RN06|RF05|O sistema deve apresentar uma mensagem de confirmação de operação quando o usuário desejar excluir uma reserva.|
|RN07|RF11|Administrador pode atualizar o cadastro de qualquer usuário.|

## 7.3 Requisitos Não-Funcionais

### 7.3.1 Arquitetura

* O sistema deve seguir a arquitetura MVC - Model-View-Controller.

### 7.3.2 Usabilidade

* O sistema deve ser responsivo, adaptando-se à plataforma que o usuário estiver utilizando.


### 7.3.3 Desempenho

* Por ser um sistema web o software necessita de uma conexão estável com a internet para seu funcionamento.

* A velocidade da internet tem impacto direto no desempenho da aplicação, sendo necessário uma velocidade suficiente para processar as informações e executar as funcionalidades do sistema.

### 7.3.4 Suportabilidade

* O sistema deve ser compatível com a versão 52 do Google Chrome.




