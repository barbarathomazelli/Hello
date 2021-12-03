# Hello FiapOn Curso.

Orientação a Objetos
Página 
2
SUMÁRIO
1 INTRODUÇÃO
................................
................................
................................
4
1.1 Linguagem de Programação
................................
................................
........
4
1.2 Introdução Java
................................
................................
............................
5
1.3 Portabilidade
................................
................................
................................
7
1.4 Orientaç
ão a objetos
................................
................................
....................
9
1.5 Princípios de Orientação a Objetos
................................
............................
12
REFERÊNCIAS
................................
................................
................................
17
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
3
LISTA DE 
FIGURAS
Figura 1.1 
–
Compilação de código Java para um SO específico
......................
7
Figura 1.2 
–
Funcionamento do processo de compilação, distribuição e execução de
código Java
................................
................................
................................
........
8
Figura 1.3 
–
Molde para construção de carros
................................
.................
10
Figura 1.4 
–
Atributos da classe Professor
................................
.......................
11
Figura 1.5 
–
Métodos da classe Professor
................................
.......................
12
Figura 1.6 
–
Princípios da programação orientada a objetos
...........................
13
Figura 1.7 
–
Herança entre classes
................................
................................
..
15
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
4
1 
INTRODUÇÃO
Nos últimos anos, o mundo presenciou uma ampla transformação tecnológica. 
Sua utilização em diversas áreas é uma realidade e seus impactos são positivos, 
trazendo 
progresso e agilidade por onde passa.
Pense em uma loja, um banco financeiro, um hospital, sua conta de telefone 
ou na sua rede social favorita. Todos eles precisam de um sistema para serem 
gerenciados. É aí que entra o Desenvolvedor de Sistemas.
Esse prof
issional de TI, tão requisitado, é fundamental na construção de 
sistemas e deve dominar conceitos básicos, entre eles: a lógica e a linguagem de 
programação.
O mercado atualmente dispõe de várias linguagens de programação para a 
construção de softwares. No
vas linguagens podem surgir e as “antigas” evoluem, 
com novas versões. 
A escolha de uma linguagem para o desenvolvimento de um sistema deve 
levar em consideração diversas variáveis estratégicas, como: maturidade da 
plataforma, custo, velocidade de desenvo
lvimento e curva de aprendizagem. 
Java vem se tornando uma plataforma de desenvolvimento das mais 
utilizadas e aceitas no mercado. Isso se deve a algumas características, como: 
portabilidade, simplicidade e entre outros que iremos elencar no decorrer do c
urso.
Aprender a linguagem Java não limita o desenvolvedor a esta plataforma. Os 
conceitos de Orientação a Objetos: Herança, Polimorfismo, Encapsulamento, 
Modularização e Abstração são aplicados a qualquer tipo de linguagem Orientada a 
Objetos (C#, VB.NET,
PHP etc.) e, a lógica de programação, estruturas de controle, 
variáveis, por exemplo, são comuns a todas elas. 
1.1 
Linguagem de Programação
Uma linguagem de programação pode ser definida como sendo um conjunto 
limitado de instruções (vocabulário), 
associado a um conjunto de regras (sintaxe) que 
define como as instruções podem ser associadas, ou seja, como se podem compor 
os programas para a resolução de um determinado problema.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
5
A  programação  em  computadores  teve  início
com  o  objetivo  de  resolver 
cál
culos matemáticos, depois 
passou a ter uso nas empresas em meados dos anos 
19
70, com objetivo da automatização de processos manuais. O formato que dominava 
a  programação  dos  sistemas
na  época  era
chamado
de
programação  linear  e 
estruturada, 
que  tem  como  ba
se  o  controle:  sequência,  condição  e  repetição,  e  a 
subprogramação (ou modularização) utilizando sub
-
rotinas e funções.
Nesta  categoria  encaixam
-
se  as  chamadas  linguagens  de  programação  de 
baixo nível, surgidas em meados dos anos 1960 como Fortran, Cobol, 
Pascal, C.
As   linguagens   concebidas   nes
s
e   período 
resultam
da   necessidade   da 
produção  de  código  de  programa  de  forma  clara,  aparecendo  o  con
ceito  de 
estruturação do código.
O período compreendido entre a
s
década
s
de 
19
60 
e 19
80 
foi   bastante   produtivo   no   q
ue   diz   respeito   ao   surgimento   de   linguagens   de 
programação,   o   que  permitiu   o   aparecimento   de   uma   grande   quantidade   de 
linguagens.
Com o aumento na produção de sistemas e com a expressa necessidade de 
reaproveitamento de códigos, este processo antes inicial
mente tão positivo, passou a 
se tornar repetitivo e trabalhoso, pois toda e qualquer atualização no sistema deveria 
ser realizada em todas as partes que eram replicadas.
Mediante 
e
sta   situação   que
,
além   do   desgaste   técnico,   causava
baixa 
produtividade  no  d
esenvolvimento  e 
peso  financeiro  às  empresas,  novas  técnicas 
surgiram para 
resolver
estes problemas. 
Desponta 
o modelo de objetos, baseado nos 
moldes já milenares da vida do ser humano. 
Trazer para a programação os conceitos de objetos 
da vida real 
e a cr
iação de 
moldes 
para esses objetos
, favoreceu toda uma nova linha de sistemas otimizados, 
r
eaproveitáveis e de fácil atualização.
1.2 
Introdução Java
A primeira versão da 
linguagem Java surgiu em 1995, criad
a
por um time de 
desenvolvedores da empresa Sun M
icrosystem, liderado por James Gosling. A ideia 
inicial  era  desenvolver  uma  linguagem  para  controlar  pequenos  dispositivos,  como 
televisores, videocassetes e aparelhos de TV a cabo. A ideia não deu certo, mas com 
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
6
o advento 
da internet, a plataforma foi ado
tada, se expandiu e evoluiu, e atualmente 
é uma referência no mercado de desenvolvimento de sistemas.
Java   se   tornou   popular   pelo   uso   na   internet   e   hoje   roda   em   muitos 
equipamentos e dispositivos: notebooks, celulares, videogames, cartões inteligentes 
etc
.
Podemos elencar várias características
-
chave para a plataforma ter alcançado 
tanto sucesso:

Simples
: 
a sintaxe do Java é uma versão limpa da sintaxe das linguagens 
da época, como C++. Não há a necessidade de arquivos de cabeçalho ou 
trabalhar  com  ponteiros  (alocar  memória  da  máquina  para  armazenar 
informações). 

Robusto
: 
Java foi concebido para desenvolve
r programas confiáveis, em 
vários   aspectos.   Existe   uma   verificação   preliminar   de   possíveis 
problemas, que em outras linguagens, só seriam descobertos em tempo 
de execução. 

Seguro
: 
Java é utilizado em ambientes de rede/distribuído. Desse modo, 
muito se tra
balhou para a segurança, deixando a plataforma livres de vírus 
e adulterações.  

Alto desempenho: 
o código Java é convertido em bytecodes (veremos 
com mais detalhes), esses bytecodes são interpretados em um ambiente 
de   execução   do   Java   para   executá
-
los.   Se
for   necessário   mais 
desempenho,  esse  ambiente  de  execução  transforma  os  bytecodes  em 
código  de  máquina  nativo  para  a  CPU  específica,  ganhando  assim 
desempenho.
Além   desses,   podemos   citar   duas   outras   características   que   foram 
determinantes para o sucesso: 
portabilidade e orientação a objetos.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
7
1.3 
Portabilidade
Entende
-
se  por  portabilidade  a  capacidade  de  ser  utilizado  em  qualquer 
plataforma, neste caso 
–
sistema operacional (Windows, Linux, Mac OS.) e hardware. 
Ou seja, Java é utilizado independente de pla
taforma.
Um  programa  Java  gerado  no  ambiente  Windows  pode,  facilmente,  ser 
executado em Linux, sem nenhuma alteração no código.
Quando  escrevemos  código  utilizando  uma  linguagem  de  programação  é 
necessário  a  conversão  desse  código  para  um  outro  código, 
de 
modo  que 
o 
computador se
ja
capaz de executá
-
lo. Esse processo possui o nome de 
compilação, 
cujo   significado   é
transformar   o   código   fonte,   que   é   mais   fácil   para   os 
desenvolvedores, em código de máquina, que é utilizado pelo computador.  
L
inguagens  como  C  e
Pascal  são  compiladas  para  um  determinado  sistema 
operacional  e  arquitetura  de  hardware,  ou  seja,  após  a  compilação,  o  código 
executável  (binário)  roda  somente  para  um  tipo  de  sistema  operacional.  Se  for 
necessário   executar   em   outro   ambiente,   será   preciso
compilar   o   programa
especificamente para esse ambiente. 
Figura 
1.
1
–
Compilação de código Java para um SO específico
Fonte: Elaborado pelo autor (2016), adaptado por FIAP (2017)
.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
8
Em algumas situações haverá necessidade de 
realizar ajustes no código, para 
o  perfeito  funcionamento  em  cada  ambiente.  Dessa  forma,  temos  um  código 
executável para cada sistema operacional.
A linguagem Java é diferente. Existe uma 
máquina virtual
, conhecida como 
JVM
(
Java Virtual Machine
), que
é ca
paz de interpretar (executar) os arquivos Java 
compilados. 
A linguagem Java é 
Compilada
e 
Interpretada
. Primeiramente, os arquivos de 
código fonte Java com extensão “.java” são compilados para 
bytecodes, 
também 
conhecidos como arquivos de extensão “.class
”.
Após  esse  processo,  os 
bytecodes
são  interpretados  pela  JVM,  iniciando  a 
execução do software. Para cada plataforma (sistema operacional + hardware) existe 
uma Máquina Virtual Java, tornando as aplicações Java portáveis.
A  imagem  abaixo  ilustra  um  códig
o  Java  sendo  compilado,  que  pode  ser 
executado em diferentes plataformas em suas respectivas JVMs.
Figura 1.
2
–
Funcionamento do processo de compilação, distribuição e execução de código Java
Fonte:
Elaborado pelo autor (2016), a
daptado por FIAP (2017).
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
=================================================================================================================================================
=================================================================================================================================================

Orientação a Objetos
Página 
2
SUMÁRIO
1 INTRODUÇÃO
................................
................................
................................
4
1.1 Linguagem de Programação
................................
................................
........
4
1.2 Introdução Java
................................
................................
............................
5
1.3 Portabilidade
................................
................................
................................
7
1.4 Orientaç
ão a objetos
................................
................................
....................
9
1.5 Princípios de Orientação a Objetos
................................
............................
12
REFERÊNCIAS
................................
................................
................................
17
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
3
LISTA DE 
FIGURAS
Figura 1.1 
–
Compilação de código Java para um SO específico
......................
7
Figura 1.2 
–
Funcionamento do processo de compilação, distribuição e execução de
código Java
................................
................................
................................
........
8
Figura 1.3 
–
Molde para construção de carros
................................
.................
10
Figura 1.4 
–
Atributos da classe Professor
................................
.......................
11
Figura 1.5 
–
Métodos da classe Professor
................................
.......................
12
Figura 1.6 
–
Princípios da programação orientada a objetos
...........................
13
Figura 1.7 
–
Herança entre classes
................................
................................
..
15
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
4
1 
INTRODUÇÃO
Nos últimos anos, o mundo presenciou uma ampla transformação tecnológica. 
Sua utilização em diversas áreas é uma realidade e seus impactos são positivos, 
trazendo 
progresso e agilidade por onde passa.
Pense em uma loja, um banco financeiro, um hospital, sua conta de telefone 
ou na sua rede social favorita. Todos eles precisam de um sistema para serem 
gerenciados. É aí que entra o Desenvolvedor de Sistemas.
Esse prof
issional de TI, tão requisitado, é fundamental na construção de 
sistemas e deve dominar conceitos básicos, entre eles: a lógica e a linguagem de 
programação.
O mercado atualmente dispõe de várias linguagens de programação para a 
construção de softwares. No
vas linguagens podem surgir e as “antigas” evoluem, 
com novas versões. 
A escolha de uma linguagem para o desenvolvimento de um sistema deve 
levar em consideração diversas variáveis estratégicas, como: maturidade da 
plataforma, custo, velocidade de desenvo
lvimento e curva de aprendizagem. 
Java vem se tornando uma plataforma de desenvolvimento das mais 
utilizadas e aceitas no mercado. Isso se deve a algumas características, como: 
portabilidade, simplicidade e entre outros que iremos elencar no decorrer do c
urso.
Aprender a linguagem Java não limita o desenvolvedor a esta plataforma. Os 
conceitos de Orientação a Objetos: Herança, Polimorfismo, Encapsulamento, 
Modularização e Abstração são aplicados a qualquer tipo de linguagem Orientada a 
Objetos (C#, VB.NET,
PHP etc.) e, a lógica de programação, estruturas de controle, 
variáveis, por exemplo, são comuns a todas elas. 
1.1 
Linguagem de Programação
Uma linguagem de programação pode ser definida como sendo um conjunto 
limitado de instruções (vocabulário), 
associado a um conjunto de regras (sintaxe) que 
define como as instruções podem ser associadas, ou seja, como se podem compor 
os programas para a resolução de um determinado problema.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
5
A  programação  em  computadores  teve  início
com  o  objetivo  de  resolver 
cál
culos matemáticos, depois 
passou a ter uso nas empresas em meados dos anos 
19
70, com objetivo da automatização de processos manuais. O formato que dominava 
a  programação  dos  sistemas
na  época  era
chamado
de
programação  linear  e 
estruturada, 
que  tem  como  ba
se  o  controle:  sequência,  condição  e  repetição,  e  a 
subprogramação (ou modularização) utilizando sub
-
rotinas e funções.
Nesta  categoria  encaixam
-
se  as  chamadas  linguagens  de  programação  de 
baixo nível, surgidas em meados dos anos 1960 como Fortran, Cobol, 
Pascal, C.
As   linguagens   concebidas   nes
s
e   período 
resultam
da   necessidade   da 
produção  de  código  de  programa  de  forma  clara,  aparecendo  o  con
ceito  de 
estruturação do código.
O período compreendido entre a
s
década
s
de 
19
60 
e 19
80 
foi   bastante   produtivo   no   q
ue   diz   respeito   ao   surgimento   de   linguagens   de 
programação,   o   que  permitiu   o   aparecimento   de   uma   grande   quantidade   de 
linguagens.
Com o aumento na produção de sistemas e com a expressa necessidade de 
reaproveitamento de códigos, este processo antes inicial
mente tão positivo, passou a 
se tornar repetitivo e trabalhoso, pois toda e qualquer atualização no sistema deveria 
ser realizada em todas as partes que eram replicadas.
Mediante 
e
sta   situação   que
,
além   do   desgaste   técnico,   causava
baixa 
produtividade  no  d
esenvolvimento  e 
peso  financeiro  às  empresas,  novas  técnicas 
surgiram para 
resolver
estes problemas. 
Desponta 
o modelo de objetos, baseado nos 
moldes já milenares da vida do ser humano. 
Trazer para a programação os conceitos de objetos 
da vida real 
e a cr
iação de 
moldes 
para esses objetos
, favoreceu toda uma nova linha de sistemas otimizados, 
r
eaproveitáveis e de fácil atualização.
1.2 
Introdução Java
A primeira versão da 
linguagem Java surgiu em 1995, criad
a
por um time de 
desenvolvedores da empresa Sun M
icrosystem, liderado por James Gosling. A ideia 
inicial  era  desenvolver  uma  linguagem  para  controlar  pequenos  dispositivos,  como 
televisores, videocassetes e aparelhos de TV a cabo. A ideia não deu certo, mas com 
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
6
o advento 
da internet, a plataforma foi ado
tada, se expandiu e evoluiu, e atualmente 
é uma referência no mercado de desenvolvimento de sistemas.
Java   se   tornou   popular   pelo   uso   na   internet   e   hoje   roda   em   muitos 
equipamentos e dispositivos: notebooks, celulares, videogames, cartões inteligentes 
etc
.
Podemos elencar várias características
-
chave para a plataforma ter alcançado 
tanto sucesso:

Simples
: 
a sintaxe do Java é uma versão limpa da sintaxe das linguagens 
da época, como C++. Não há a necessidade de arquivos de cabeçalho ou 
trabalhar  com  ponteiros  (alocar  memória  da  máquina  para  armazenar 
informações). 

Robusto
: 
Java foi concebido para desenvolve
r programas confiáveis, em 
vários   aspectos.   Existe   uma   verificação   preliminar   de   possíveis 
problemas, que em outras linguagens, só seriam descobertos em tempo 
de execução. 

Seguro
: 
Java é utilizado em ambientes de rede/distribuído. Desse modo, 
muito se tra
balhou para a segurança, deixando a plataforma livres de vírus 
e adulterações.  

Alto desempenho: 
o código Java é convertido em bytecodes (veremos 
com mais detalhes), esses bytecodes são interpretados em um ambiente 
de   execução   do   Java   para   executá
-
los.   Se
for   necessário   mais 
desempenho,  esse  ambiente  de  execução  transforma  os  bytecodes  em 
código  de  máquina  nativo  para  a  CPU  específica,  ganhando  assim 
desempenho.
Além   desses,   podemos   citar   duas   outras   características   que   foram 
determinantes para o sucesso: 
portabilidade e orientação a objetos.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
7
1.3 
Portabilidade
Entende
-
se  por  portabilidade  a  capacidade  de  ser  utilizado  em  qualquer 
plataforma, neste caso 
–
sistema operacional (Windows, Linux, Mac OS.) e hardware. 
Ou seja, Java é utilizado independente de pla
taforma.
Um  programa  Java  gerado  no  ambiente  Windows  pode,  facilmente,  ser 
executado em Linux, sem nenhuma alteração no código.
Quando  escrevemos  código  utilizando  uma  linguagem  de  programação  é 
necessário  a  conversão  desse  código  para  um  outro  código, 
de 
modo  que 
o 
computador se
ja
capaz de executá
-
lo. Esse processo possui o nome de 
compilação, 
cujo   significado   é
transformar   o   código   fonte,   que   é   mais   fácil   para   os 
desenvolvedores, em código de máquina, que é utilizado pelo computador.  
L
inguagens  como  C  e
Pascal  são  compiladas  para  um  determinado  sistema 
operacional  e  arquitetura  de  hardware,  ou  seja,  após  a  compilação,  o  código 
executável  (binário)  roda  somente  para  um  tipo  de  sistema  operacional.  Se  for 
necessário   executar   em   outro   ambiente,   será   preciso
compilar   o   programa
especificamente para esse ambiente. 
Figura 
1.
1
–
Compilação de código Java para um SO específico
Fonte: Elaborado pelo autor (2016), adaptado por FIAP (2017)
.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Orientação a Objetos
Página 
8
Em algumas situações haverá necessidade de 
realizar ajustes no código, para 
o  perfeito  funcionamento  em  cada  ambiente.  Dessa  forma,  temos  um  código 
executável para cada sistema operacional.
A linguagem Java é diferente. Existe uma 
máquina virtual
, conhecida como 
JVM
(
Java Virtual Machine
), que
é ca
paz de interpretar (executar) os arquivos Java 
compilados. 
A linguagem Java é 
Compilada
e 
Interpretada
. Primeiramente, os arquivos de 
código fonte Java com extensão “.java” são compilados para 
bytecodes, 
também 
conhecidos como arquivos de extensão “.class
”.
Após  esse  processo,  os 
bytecodes
são  interpretados  pela  JVM,  iniciando  a 
execução do software. Para cada plataforma (sistema operacional + hardware) existe 
uma Máquina Virtual Java, tornando as aplicações Java portáveis.
A  imagem  abaixo  ilustra  um  códig
o  Java  sendo  compilado,  que  pode  ser 
executado em diferentes plataformas em suas respectivas JVMs.
Figura 1.
2
–
Funcionamento do processo de compilação, distribuição e execução de código Java
Fonte:
Elaborado pelo autor (2016), a
daptado por FIAP (2017).
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com

====================================================================================================================================================

Exceptions + vários outros, design 
patters
Página 
4
LISTA DE TABELAS
Tabela 1.1 
–
Exemplo de tabela a ser utilizado.
................................
.......................
9
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Exceptions + vários outros, design patters
Página 
5
LISTA DE CÓDIGOS
-
FON
TE
Código Fonte 1.1 
–
Exemplo de código
-
fonte HTML.
................................
...............
8
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Exceptions + vários outros, design patters
Página 
6
SUMÁRIO
6 
EXCEPTIONS E CONCEIT
OS AVANÇADOS DE ORIE
NTAÇÃO A OBJETOS
....
7
6.1 Tratamento de exceções
................................
................................
.....................
7
6.2 Classificação
................................
................................
................................
.......
8
6.3 Captura e Tratamento de Exceções
................................
................................
....
10
6.4 Propagação de exceções 
–
Throws
................................
................................
....
16
6.5 Criação de exceções
................................
................................
...........................
18
6.6 Acesso a arquivos
................................
................................
...............................
20
6.7 Polimorfismo
................................
................................
................................
........
31
6.8 Classe abstrata
................................
................................
................................
...
33
6.9 Modi
ficador final
................................
................................
................................
..
37
6.10 Modificador static
................................
................................
...............................
40
6.11 Constantes
................................
................................
................................
........
43
6.12 Interfa
ces:
................................
................................
................................
..........
44
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
===================================================================================================================================================

Exceptions + vários outros, design 
patters
Página 
4
LISTA DE TABELAS
Tabela 1.1 
–
Exemplo de tabela a ser utilizado.
................................
.......................
9
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Exceptions + vários outros, design patters
Página 
5
LISTA DE CÓDIGOS
-
FON
TE
Código Fonte 1.1 
–
Exemplo de código
-
fonte HTML.
................................
...............
8
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Exceptions + vários outros, design patters
Página 
6
SUMÁRIO
6 
EXCEPTIONS E CONCEIT
OS AVANÇADOS DE ORIE
NTAÇÃO A OBJETOS
....
7
6.1 Tratamento de exceções
................................
................................
.....................
7
6.2 Classificação
................................
................................
................................
.......
8
6.3 Captura e Tratamento de Exceções
................................
................................
....
10
6.4 Propagação de exceções 
–
Throws
................................
................................
....
16
6.5 Criação de exceções
................................
................................
...........................
18
6.6 Acesso a arquivos
................................
................................
...............................
20
6.7 Polimorfismo
................................
................................
................................
........
31
6.8 Classe abstrata
................................
................................
................................
...
33
6.9 Modi
ficador final
................................
................................
................................
..
37
6.10 Modificador static
................................
................................
...............................
40
6.11 Constantes
................................
................................
................................
........
43
6.12 Interfa
ces:
................................
................................
................................
..........
44
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
=====================================================================================================================================================


Acesso ao Banco de Dados
Página 
4
LISTA DE 
TABELA
S
Tabela 7.1 
–
TABELA WHERE CONDICAO1
................................
...........................
18
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Acesso ao Banco de Dados
Página 
5
SUMÁRIO
7 ACESSO AO BANCO DE
DADOS
................................
................................
.........
6
7.1 Introdução
................................
................................
................................
...........
6
7.1 Java Datab
ase Connectivity
................................
................................
................
8
7.2 Banco de dados oracle e comandos sql
................................
..............................
12
7.2.1 Cadastrando informações na tabela
................................
................................
.
15
7.2.2 Leitura de dados de 
uma tabela
................................
................................
.......
17
7.2.3 Atualizando valores na tabela
................................
................................
..........
20
7.2.4 Remoção de registros de uma tabela (Delete)
................................
.................
21
7.2.5 Conectando a base de
dados
................................
................................
...........
2
1
7.2.6 Statements
................................
................................
................................
.......
26
7.2.7 CallableStatement
................................
................................
............................
31
7.3 Controle transacional
................................
................................
...........................
48
7.3.1 Transação
................................
................................
................................
........
48
7.4 
Design patterns
................................
................................
................................
...
51
7.4.1 Data Access Object (DAO)
................................
................................
...............
52
7.4.2 DAO Factory
................................
................................
................................
.....
65
7.4.3 Abst
ract Factory
................................
................................
...............................
68
7.4.4 Singleton
................................
................................
................................
..........
71
REFERÊNCIAS
................................
................................
................................
.........
74
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com
Acesso ao Banco de Dados
Página 
6
7
ACESSO AO BANCO DE D
ADOS
7
.1 
Introdução
A  maioria  dos  sistemas  precisa  armazenar  dados  e  informações  para 
serem 
recuperados  posteriormente.  Por  exemplo,  um  sistema  bancário  precisa  registrar 
várias informações, entre eles os saques e depósitos para manter o saldo da conta 
atualizada.  Um  sistema  de  vendas  online  deve  armazenar  todos  os  dados  de  seus 
clientes, p
rodutos, fornecedores, vendas etc.
Uma  solução  é  armazenar  as  informações  em  arquivos  textos  e  planilhas. 
Porém, por se tratar de uma grande 
quantidade de informações, é difícil de manter o 
gerenciamento dos dados, e com certeza qualquer acesso a essas inf
ormações será 
com pouca performance
e utilizando bastante processamento. Outra opção é utilizar 
sistemas   especializados   no   armazenamento   de   dados   que   oferecem   mais 
funcionalidades e recursos avançados, como backup e buscas mais eficientes. Esses 
sistemas  s
ão  conhecidos  como: 
Sistemas  Gerenciadores  de  Banco  de  Dados 
–
SGBD.
Um  Sistema  de  Gerenciamento  de  Banco  de  Dados  é  um  conjunto  de 
programas de computador responsáveis pelo gerenciamento de uma base de dados. 
Seu principal objetivo é retirar da aplicação 
cliente a responsabilidade de gerenciar o 
acesso, manipulação e a organização dos dados. O SGBD disponibiliza uma interface 
para que seus clientes possam realizar as operações de inclusão, alteração, exclusão 
e consulta de dados.
Os  principais  SGBDs  utiliz
ados  nas  empresas  aplicam  o  Modelo  Relacional 
para  armazenar  informações
,  e  a  linguagem  SQL  é  utilizada  para  realizar  as 
operações nas base
s
de dados.
Os principais SGBDs utilizados no mercado são:

Oracle Database.

Microsoft SQL Server.

PostgreSQL.

Sysbase
.
PDF exclusivo para Barbara Thomazelli - barbarathomazelli@gmail.com
barbarathomazelli@gmail.com

