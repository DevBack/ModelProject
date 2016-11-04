# 1. Planejamento da Sprint
O foco desta sprint reside na implementação das histórias técnicas e histórias de testes definidas com base nas lacunas de desenvolvimento deixadas até a Release 1. 

## 1.1. Papéis

|Scrum Master|Product Owner|Development Team     |
|------------|-------------|---------------------|
|Allan       | Elaine      |<ul><li>Fabiola</li><li>Gustavo</li><li>Hugo</li><li>Jessica</li><li>Lucas</li><li>Luís</li><li>Pedro</li><li>Vitor</li>  |

## 1.2. Backlog

| TS (Technical Story) | História | Pontuação | Responsável |
|----------------------|----------|-----------|-------------|
| #1 | Como um desenvolvedor, eu quero criar um app de usuário para melhorar a gerência dos usuários. | 3  | Gustavo e Vitor |
| #2 | Como um desenvolvedor, eu quero realizar as validações necessárias do cadastro de usuário para garantir a consistência dos dados inseridos. | 5  | Elaine e Hugo |
| #3 | Como um desenvolvedor, eu quero testar o cadastro de usuário para garantir a funcionalidade do método.| 3 | Elaine e Hugo |
| #4 | Como um desenvolvedor, eu quero realizar as validações necessárias da alteração de usuário para garantir a consistência dos dados inseridos. | 3 | Jessica e Fabíola |
| #5 | Como um desenvolvedor, eu quero testar a alteração de usuário para garantir a funcionalidade do método. | 3 | Jessica e Fabíola |
| #6 | Como um desenvolvedor, eu quero testar a exclusão de usuário para garantir a funcionalidade do método. | 2 | Jessica e Fabíola |
| #8 | Como um desenvolvedor, eu quero realizar as validações necessárias do login de usuário para garantir a consistência dos dados inseridos. | 2 | Gustavo e Vitor |
| #9 | Como um desenvolvedor, eu quero testar o login e logout de usuário para garantir a funcionalidade do método. | 3 | Gustavo e Vitor |
| #10 | Como um desenvolvedor, eu quero realizar as validações necessárias da criação de reserva para garantir a consistência dos dados inseridos. | 8 | Pedro e Luís |
| #12 | Como um desenvolvedor, eu quero refatorar o cadastro de criação de reserva para consertar os bugs conhecidos. | 8 | Allan e Lucas |
| **Total** |   | **40** ||

## 1.3. Quadro de Conhecimentos
Para monitorar e controlar as habilidades da equipe, necessárias para o desenvolvimento do projeto, foi usado o seguinte quadro de conhecimento.
![Quadro de Conhecimentos](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/0_conhecimento.png) 

## 1.4. Quadro de pareamento
Levando em consideração as necessidades técnicas da estorias priorizadas para sprint e quadro de conhecimentos, foram planejados e executados os seguintes pareamentos.
![Quadro de Pareamento](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/0_pareamento.png) 

## 1.5. Restrospectiva
| Pontos Positivos |
|------------------|
| Aumento da cobertura de testes | 
| Foco em código | 
| Aumento da interação entre o time |

|Pontos Negativos |Causa| Melhoria|
|-----------------|-----|---------|
|Não finalização da sprint |Dificuldade de parear |Deixar o pareamento livre entre todos os membros|
|Atraso nas Reuniões|Horário da reunião |Votação para decidir o melhor horário da reunião para todos|
|Histórias dependentes umas das outras | As histórias foram mal divididas| Tentar designar histórias dependentes para o mesmo par|
|Dependência de GPP para parear|O pareamento foi divido fixo, com um de GPP e um de MDS|Designar um membro de MDS como responsável da história, onde o mesmo deve procurar qualquer outro integrante do SAS para parear |
|Desenvolvimento desuniforme ao longo da sprint|Pareamento fixo |Parear sempre com quem estiver disponível no momento|

# 2. Resultados:

## 2.1. Burndown
Durante a sprint 0, o time não distribuiu os pontos uniformemente durante seu tempo, como pode ser observado no gráfico abaixo, concentrando seus esforços durante o início e fim da mesma. Além disso, um débito de 16 pontos foi registrado, devido a problemas de comunicação, tempo de pareamento e dificuldade da história.

![Sprint 0 - Burndown](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/0_burndown.png) 

## 2.2 Velocity
O velocity desta sprint foi de **24 pontos**. Como esta é a primeira sprint, esta pontuação refere-se a quantidade total completada durante o período de 01/10/2016 a 07/10/2016.

![Velocity](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/0_velocity.png)

## 2.3 Agile EVM

![EVM](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/img/0_evm.png)

**OBS.** As descrições e fórmulas das siglas apresentadas na tabela acima estão devidamente explicitadas [aqui](https://github.com/fga-gpp-mds/2016.2-SAS_FGA/wiki/Agile-EVM).

Foram planejado 40 pontos para essa Sprint, e entregues 24. O RPC (Pontos Completos Na Release) ficou então em 24, já que essa é a primeira sprint, e o APC (Porcentagem Completa Real) ficou em 16,22% acima do PPC (Porcentagem Planejada Completa) de 12,50, o que indica um bom andamento do projeto. Não foi adicionado nenhum ponto novo ao projeto, PA (Pontos Adicionados) = 0.

## 2.4. Qualidade
### 2.4.1 Integração Contínua
A integração contínua do projeto está passando nas duas principais branchs do projeto: master e dev. A imagem abaixo demonstra esse status.

![Travis CI](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint0/travis.png) 

### 2.4.2 Cobertura de Teste
Desde a última release (R1) a cobertura de teste obteve um aumento significativo de 49,56% para 68,49%. A imagem abaixo demonstra esse crescimento.

![Coveralls](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time05-SalasFGA/metrics/sprint0/coveralls.png)

