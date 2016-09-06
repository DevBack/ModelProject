# Histórico de revisões deste documento

|Data       |Versão|Descrição     |Autor  |
|-----------|------|--------------|-------|
| 04/09/2016| 1.0  | Criação e preenchimento da estrutura inicial da folha de estilo| Elaine|
| 04/09/2016| 1.2  | Adequação da folha de estilo ao PEP 8| Pedro|

## 1. Introdução

O presente documento foi baseado no **Guia de Estilo PEP 8** e demonstra uma convenção para codificação em linguagem Python, a qual será utilizada no desenvolvimento do projeto SAS - Sistema de Alocação de Salas. Tal estilo será aplicado no projeto a fim de uma padronização, organização e manutenabilidade do código. 

## 2. Formatação do Código

### 2.1 Identação
A identação a ser utilizada em todos os arquivos de código do projeto deve ser de 4 espaços. Cada vez que um nível é abaixado, como em casos de códigos dentro de condicionais e funções, por exemplo, além de quebras de linhas causadas por extrapolação do limite máximo de caracteres, a identação deve ser usada.

### 2.2 Tamanho de Linhas e Linhas em Branco

#### 2.2.1 Tamanho da Linha
Em todo o projeto e seus arquivos, o tamanho da linha será limitado a 79 caracteres. Assim, sempre que surgir a necessidade de uma quebra de linha, a mesma será realizada através da adição de uma barra invertida (\) inserida após o operador binário (and, or).

#### 2.2.2 Linhas em Branco
As linhas em branco podem ser utilizadas nas seguintes situações:
* Duas linhas em branco para separação de funções de nível superior e definições de classe;
* Uma linha em branco para definições de método dentro de uma classe, separação de grupos de funções e importações; e indicação de seções lógicas;
Linhas em branco não devem conter nehum espaço em branco, deve-se apagar as tabulações nas linas em branco.
### 2.3 Importações
Todas as importações a serem utilizadas devem estar alocadas no início do arquivo, antes de declaração de variáveis globais e constantes, e depois de comentários e docstrings de módulo, caso existam. Além disso, as mesmas devem estar em linhas separadas e não separadas por vírgulas, exceto quando pertencem a um mesmo módulo.

As importações devem seguir a seguinte ordenação:
* Da biblioteca padrão;
* De terceiros;
* Locais, da aplicação.

### 2.4 Espaços em Branco
Sempre deve haver espaços em branco entre operadores. Porém, estes devem ser evitados:

* Ao final de linhas;
* Para alinhar resultados de variáveis com nomes de tamanhos diferentes;
* Ao redor de o igual (=) quando este é uma palavra-chave de um argumento ou um valor padrão para um parâmetro;
* Imediatamente após a abertura de parêntesis, colchetes ou chaves; 
* Imediatamente antes de: 
  *  Vírgulas, ponto-e-vírgulas e dois-pontos;
  * Parêntesis referentes a lista de argumentos de uma função;
  * Colchete de índices/fatias;

### 2.5 Comentários
Comentários somente devem ser usados em caso de o código não demonstrar uma ação em sua obviedade. Além disso, é aconselhável que seu uso seja realizado na linha anterior a ação, e não na mesma linha. Deve-se iniciá-lo com um jogo da velha (#), um espaço, o texto desejado, começando com letra maiúscula, e, finalmente, dois espaços após o fim da oração.

### 2.6 Convenções de nomenclatura
||Padrão|
|------|---------------------------|
|Classes|Os nomes devem seguir o padrão camelcase, ou seja iniciar com letra maiúscula todas as palavas e não separa-las com underscores.|
|Métodos|Os nomes devem ser escritos com letras minúsculas com palavras separadas por underscores.|
|Variáveis|Os nomes devem ser escritos com letras minúsculas com palavras separadas por underscores.|
|Constantes|Os nomes devem ser escritos com letras maiúsculas com palavras separadas por underscores.|

  
