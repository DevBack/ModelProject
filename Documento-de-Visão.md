# Histórico de revisões deste documento

|Data|Versão|Descrição|Autor|
|----|------|---------|-------|
|20/08/2016 |1.0 |Introdução |Lucas |
|20/08/2016 |1.1 |Visão Geral do Produto |Vítor |
|20/08/2016 |1.2 |Recursos do Produto |Hugo |
|20/08/2016 |1.3 |Posicionamento |Luis |
|20/08/2016 |1.4 |Descrição dos Envolvidos e dos Usuários |Fabíola |
|20/08/2016 |1.5 |Revisão da Visão Geral do Produto |Vítor |

# Introdução
  
Este documento tem como objetivo definir o escopo, a proposta, os recursos do produto, o problema a ser resolvido, quem terá acesso ao produto, assim como o tipo de acesso. O cliente do sistema realiza a locação de salas de forma manual. O objetivo do projeto é criar um sistema que automatize esse processo, evitando erros, como duas salas locadas para a mesma pessoa no mesmo horário,  tornando-o ágil.

# Posicionamento

## Oportunidade de Negócio

No estado atual, a alocação de salas é feita por cada coordenador da maneira que o mesmo acha mais adequado, através do uso de planilhas excel e planilhas manuais. Desse modo são encontrados vários problemas na reserva de salas, pois para sua alocação cabe a cada coordenador conferir manualmente em sua planilha a disponibilidade da sala em determinado horário.
Assim o SAS vêm como solução para automatizar esse processo, tornando mais prático a alocação de salas, evitar problemas como, por exemplo, reservar uma mesma sala no mesmo horário para duas atividades diferentes e facilitar o processo para os coordenadores.

## Declaração do Problema

|||
|---|---|
|**O problema de** | Fazer alocação de salas manualmente com o excel |
|**Afeta** | Administrador e corpo acadêmico |
|**Cujo impacto é** | Alocação de salas a mais, choques de horários de salas e professores e alunos não podem fazer reservas |
|**Uma boa solução seria** | Um sistema web para alocação de salas |

## Declaração da Posição do Produto

|||
|---|---|
|**Para**| Docentes, Discentes e demais membros do Corpo Acadêmico da UnB Gama|
|**Que**| Deseja gerenciar a alocação de salas com rapidez e eficiência|
|**Sistema de Alocação de  Salas(SAS)**|  É um produto de software|
|**Que**| Um sistema web para alocação de salas|
|**Diferente**| Do estado atual que requer que o administrador altere manualmente os horários e quem ocupará as salas|
|**Nosso produto**| Controla as informações relativas as salas, seus respectivos horários e sua disponibilidade e permite reserva das salas|

# Descrição dos Envolvidos e dos Usuários
##Resumo dos Envolvidos
|Nome|Descrição|Responsabilidades|Representantes|
|----|------|---------|------------|
|Cliente |Requisitou o sistema |Fornece os requisitos do sistema |Carla Rocha Aguiar|
|Gerentes |Gerenciam o projeto |Elaboram os planos de projeto, Monitoram o andamento do projeto, Revisam o projeto, Auxiliam a equipe de desenvolvimento |Allan Pereira,  Elaine Meirelles, Gustavo Coelho, Jessica Suzuki, Pedro Alcântara|
|Desenvolvedores |Desenvolvem o sistema |Documentação e programação |Fabíola Malta,  Hugo Carvalho, Luis Gustavo, Lucas Oliveira, Vítor Gomes|

##Resumo dos Usuários
|Nome|Descrição|Responsabilidades|Representantes|
|----|------|---------|------------|
|Administrador|Usuário final do sistema |Reserva salas,Controla reservas |Coordenadores|
|Usuário | Usuário final do sistema|Reserva salas |Professores, estudantes, técnicos administrativos e demais integrantes do Corpo Acadêmico|
##Ambiente do Usuário
* A cliente utiliza uma planilha do Excel para gerenciar a utilização das salas.
* A organização de salas com os horários de professores e matérias é feita pela cliente. de forma não automatizada, portanto esta suscetível a diversos erros e requer muito tempo.
* A secretaria é responsável por mediar reserva de salas e laboratórios para alunos.
* A reserva efetuada pela secretaria não é digital, sendo anotada em uma planilha física.
* O sistema que será desenvolvido agilizará o processo de alocação de salas.
* O sistema mudará o processo, que não será feito apenas pela secretaria e pela cliente, possibilitando o acesso para o Corpo Acadêmico.

##Principais necessidades dos usuários ou dos envolvidos

A solução utilizada para alocar salas de aulas é pouco prática, feita em excel e manualmente. Isso permite a existência de choques de horários em salas e múltiplas salas reservadas pela mesma pessoa e mesmo horário. 
O sistema que será desenvolvido não permite a reserva de uma sala que já está alocada, e permite uma melhor visualização das salas.


|Necessidade|Solução Atual|Solução Proposta|
|----|------|---------|------------|
|----|------|---------|------------|
# Visão Geral do Produto

Esta seção expõe uma visão ampla do produto, explicando aspectos gerais de seus recursos.

## Perspectiva do Produto

No atual contexto do ambiente acadêmico da Universidade de Brasília, constata-se uma crescente necessidade por um sistema que facilite a alocação de salas por discentes, docentes e demais integrantes do corpo acadêmico – seja para apresentações de Trabalhos de Conclusão de Curso, aulas de monitoria ou tutoria, dentre outros – visto que, hoje, tal procedimento demanda um longo processo e burocracia. 

## Sumário de Capacidades

Tabela 1 – Benefícios do Usuário e Recursos de Suporte

|Benefícios do Usuário|Recursos de Suporte|
|---------------------|-------------------|
|Alocação da sala feita mais rapidamente.|O processo de análise do pedido, verificando se a sala no horário requerido está livre, é otimizado.|
|Não há choque de horários (mais de uma sala reservada para a mesma pessoa no mesmo horário ou uma sala reservada para mais de uma pessoa no mesmo horário).|O sistema analisa se a sala já possui reservas no horário ou se o usuário já possui uma reserva neste horário, impedindo outra reserva.|

## Suposições e Dependências

O sistema será utilizado pelo usuário através da internet, logo, há custos de hospedagem. Assim, supõe-se que o cliente arcará com estes valores para que o sistema permaneça online.

## Licença e Instalação

Como o sistema estará disponível online, o licenciamento se dá a partir da aceitação dos termos e condições de uso do sistema por parte do usuário. Além disso, não há necessidade de instalação, precisando apenas do acesso a internet e de um navegador web.

# Recursos do Produto
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

## Restrições

### Restrições de implementação

* O sistema deve ser implementado utilização web, na linguagem Python, fazendo uso da framework Django.
* O sistema deve seguir a arquitetura MVC - Model-View-Controller.

### Restrições do sistema

* O sistema deve ser compatível com a versão 52.0.2743.116 m do Google Chrome.
* O sistema deve ser responsivo, adaptando-se à plataforma que o usuário estiver utilizando.

### Restrições de confiabilidade

* O sistema deve ter cobertura de erros e exceções - mínimo de 90%;