## SGBD
Sistema Gerenciador de Bando de Dados

# Banco De Dados
 
 banco de dados é um sistema que armazena dados e possui ferramentas para gerenciar esses dados ele também representa um mini mundo 

## Tabelas 

são estruturas onde ficam armazenados os dados

## Campos ou Atributos

é uma parcela da informação, ele vai ter nome e tipos de dados

## Linhas dou Tupla

são os registros 

## DCL
  **Data Control Language.**
  A Data Control Language é a sub-língua responsável pelas tarefas administrativas de controle do próprio banco de dados, principalmente a concessão e revogação de permissões de banco de dados para os usuários. Em SQL, isto corresponde aos comandos `GRANT`, `REVOKE`, e `DENY`, entre outros.
## DML
 **Data Manipulation Language.**
  A Data Manipulation Language é o sub idioma responsável pela adição, edição ou exclusão de dados de um banco de dados. Em SQL, isto corresponde ao `INSERT`, `UPDATE`, e `DELETE`
## DDL
 **Data Definition Language.**
  A linguagem de definição de dados é a sub-língua responsável pela definição da forma como os dados são estruturados em um banco de dados. Em SQL, isto corresponde à manipulação de tabelas através do `CREATE TABLE`, `ALTER TABLE` e `DROP TABLE`
 
 # Trabalhando com MySQL

 ## Conectando
 `mysql -h localhost -u root`, -h é o host, -u é o usúario e -p vai ter que digitar senha
 
 ## Mostra os Bancos de Dados
`show databases;`

## Para se conectar com Bd
 use (nome do bd;)

## Para excluir um Banco de Dados
`drop databases;`

## Para criar um Banco de dados e usa-lo
`create database (nome do banco de dados);` e para usar `use(nome do banco de dados);`

## Estrutura da tabela

para ver a estrutura da tabela se `usa desc jogos;`

##  Atividade 👨‍💻

1.	O que é um Sistema Gerenciador de Banco de Dados?
r: SGBD é o sitema que será utilizado para o manuseio do banco de dados, como proteger e organizar

2.	O que é um Banco de dados relacional?
r: um banco de dados relacional é o que tem informações relacionadas em cada tabela, significa que não tem uma ramificação de ordem mas sim relações

3.	O que é T-SQL?
Transact-SQL é a linguagem utilizada para controlar o banco de dados, fazer perguntas para saber informações das tabelas.

4.	O que é PL/SQL?
r: Linguagem de Programação Procedural é a linguagem que utilizam para criar banco de dados para aplicativos e utilizando instruções você diz ao banco de dados oque fazer


5.	T-SQL e PL/SQL são iguais? Caso não sejam, cite 3 diferenças entre elas.
r: não são iguais elas tem diferença em sintaxe, desempenho e funções 

6.	O Que é:
A.	DML: como já diz na sigla é a manipulação do código como inserir informações e deletar

B.	DDL: Utilizamos essa sub-língua para fazer as estruturas do banco de dados, em sql é a manipulação de tabelas

C.	DCL: responsável pela parte administrativa do banco de dados como dar permissões para usuários
