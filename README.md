# data-analyst-questions

Nome:
Cargo: 


1 - Um dos modelos mais utilizados no projeto e implementação de um data warehouse é o modelo dimensional ou multidimensional. Em um modelo dimensional (composto por uma tabela fato e várias tabelas dimensão),

A)	as tabelas dimensão devem conter apenas atributos do tipo literal.

B)	a tabela fato tem uma cardinalidade de mapeamento de um para um com cada tabela dimensão.

C)	não há limitação quanto ao número de tabelas dimensão.

D)	há um número teórico mínimo de 3 e máximo de 15 tabelas dimensão.

E)	a tabela fato não deve possuir atributos do tipo numérico.



2 - Existem dois esquemas lógicos para a implementação de um modelo de BI que envolve tabelas de fato e tabelas de dimensões: o esquema estrela (star schema) e o floco-de-neve (snow-flakeschema). Acerca do esquema estrela, assinale a opção correta:

A)	No esquema estrela, diversas tabelas de dimensão se relacionam tanto com diversas tabelas fato como com outras tabelas de dimensão, apresentando chaves ligando todas essas tabelas.

B)	No esquema estrela, as tabelas de dimensão são organizadas em uma hierarquia por meio da sua normalização, com vistas a diminuir o espaço ocupado, eliminando-se, assim, quaisquer redundâncias.

C)	O esquema estrela exige o uso de tabelas normalizadas.

D)	No esquema estrela, cada tabela de dimensão está relacionada a várias tabelas de fato, formando uma estrutura na qual a tabela de dimensão se relaciona com várias tabelas de fato obrigatoriamente.

E)	O esquema estrela consiste em uma tabela de fato com várias tabelas para cada dimensão e propõe uma visão cuja principal característica é a presença de dados redundantes nas tabelas de dimensão.


3 - De acordo com a estrutura abaixo:

![image](https://user-images.githubusercontent.com/94984977/143281043-c5184b15-8949-41fb-9bd2-ba4f3b546307.png)

 
 Escreva uma consulta em SQL Server resolvendo as questões abaixo:

A)	Pesquise os itens que foram vendidos sem desconto. As colunas presentes no resultado da consulta são: ID_NF, ID_ITEM, COD_PROD E VALOR_UNIT.

B)	Higienize sua consulta tratando o valor do desconto (para zero) de todos os registros onde este campo é nulo.

C)	Pesquise o valor total das NF e ordene o resultado do maior valor para o menor. As colunas presentes no resultado da consulta são: ID_NF, VALOR_TOTAL. O VALOR_TOTAL é obtido pela fórmula: ∑ QUANTIDADE * VALOR_UNIT. Agrupe o resultado da consulta por ID_NF.

D)	Consulte o produto que mais vendeu no geral. As colunas presentes no resultado da consulta são: COD_PROD, QUANTIDADE. Agrupe o resultado da consulta por COD_PROD.

E)	Quais as NF que possuem mais de 3 itens vendidos. As colunas presentes no resultado da consulta são: ID_NF, QTD_ITENS. OBS:: NÃO ESTÁ RELACIONADO A QUANTIDADE VENDIDA DO ITEM 

E SIM A QUANTIDADE DE ITENS POR NOTA FISCAL. Agrupe o resultado da consulta por ID_NF.



4 - Julgue os próximos itens, no que diz respeito a comandos SQL de consulta:


I. Subqueries de múltiplas colunas retornam várias colunas em uma mesma linha.

II. A função UNION apresenta as linhas que existem simultaneamente em duas ou mais tabelas.

III. A função EXISTS garante que o resultado de uma subquery somente seja mostrado se retornar uma ou mais linhas.

IV. A função EXTRACT retorna uma das informações de um campo do tipo data (dia, mês, ano, hora, minuto ou segundo).

Assinale a opção correta.

A)	I e II.

B)	I e IV.

C)	II e III.

D)	III e IV.

E)	Todos os itens estão certos.


5 - Em um select usando duas tabelas, para retornar todas as linhas da tabela utilizada na cláusula from, mesmo se não houver nenhuma correspondência na outra tabela, deve-se utilizar a palavra chavesql:

A)	RIGHT JOIN.

B)	LEFT JOIN.

C)	INNER JOIN.

D)	UNION.

E)	FULL OUTER JOIN.


6 - Usado para combinar o resultado conjunto de duas ou mais instruções select, considerando que cada select deve ter o mesmo número de colunas, as quais devem ter tipos de dados similares. Além disso, as colunas em cada instrução selectdevem estar na mesma ordem. Trata-se de:


A)	LIKE.

B)	UNION.

C)	JOIN.

D)	BETWEEN.

E)	FORMAT.


7 - Quando se trabalha com os comandos da SQL, deve-se dar atenção à precedência entre os operadores. Assim, se vários operadores aparecerem em uma expressão, alguns deverão ser executados antes dos outros. A ordem de precedência, que estabelece os operadores que primeiro são executados para os que devem ser executados por último, está indicada na seguinte alternativa:



A)	(), NOT, AND e OR.

B)	NOT, AND, OR e ().

C)	AND, OR, () e NOT.

D)	OR, (), NOT e AND.

E)	AND, NOT, () e OR.

