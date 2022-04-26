# SQL
Estudo sobre SQL


SQL:
-Uma forma de dar instruções para o banco de dados conseguindo assim consultar ou
manipular os dados (adicionar remover, alterar etc.)
-Para consultar dados no banco é usado o comando SELECT * FROM nome da tabela, porém
você pode adicionar mais condições a consulta
-Caso você queira ignorar alguma parte da consulta é usado um 'S%'
-Para criar um banco de dados é usado o comando CREATE DATABASE nome do banco
-Para criar uma tabela é usado o comando CREATE TABLE nome da tabela.
Not null:
O valor não pode ser nulo
Auto increment:
Os valores serão adicionados de forma automática de acordo com a criação de campos
dentro da tabela
-Para inserir dados dentro de uma tabela é usado o comando INSERT INTO nome da tabela,
passando os campos e os valores desejados.

Funções agregadas:
Calculam valores usando os dados dos registros através de comando como o COUNT, que
conta o número de registro específicos

Existem vários outros comandos como o ORDER BY, que define a forma que a tabela será
organizada, o UPDATE TABLE que atualiza os dados das tabelas, ou o JOIN nome da tabela ON
nome da tabela.campo da tabela = Tabela.campo desejado para busca, que irá juntar os
valores de duas ou mais tabelas durante a consulta, entre outros
Exemplo Join on:
SELECT * FROM Pedidos
JOIN Clientes ON Pedidos.clientesId = Clientes.id

JOIN:
Forma de juntar duas tabelas durante a consulta
Existem vários Joins, alguns deles são:
INNER JOIN
LEFT (OUTER) JOIN
RIGHT (OUTER) JOIN

-Para agrupar os resultados das consultas é usada a cláusula GROUP BY

Dados:
Existem diversos tipos de dados que podem ser usados desde Varchar (basicamente uma
String) a Binary (boleano)

-É possível utilizar operações matemáticas para consultar e calcular dados

SubQuery:
Algumas cláusulas necessitam do comando SELECT para funcionarem, para isso podemos fazer
uma consulta dentro da consulta

Transformando seus dados:
Podemos definir a forma em que os dados irão aparecer durante a consulta (em letras
maiúsculas (UPPER) ou não (LOWER), como os dados serão separados (SUBSTR), ou apenas
substituir algum caractere (REPLACE))

Alias:
Basicamente é um apelido para a coluna ou tabela, facilitando quando for realizar uma
consulta.
