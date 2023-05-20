# Curso SQL Completo 
 
## Introdução a Banco de Dados 
* SGBD: Sistema Gerenciador de Banco de Dados;
* SQL: Linguagem Estruturada de Consulta;
* DDL (Data Definition Language): Linguagem de Definição de Dados (CREATE, ALTER, DROP);
* DML (Data Manipulation Language): Linguagem de Manipulação de Dados (INSERT, UPDATE, DELETE);
* DQL (Data Query Language): Linguagem de Consulta de Dados (SELECT);
* DCL (Data Control Language): Linguagem de Controle de Dados (GRANT, REVOKE)
* DTL (Data Transaction Language): Linguagem de Transação de Dados (START TRANSACTION, COMMIT, ROLLBACK);
* Unsigned: o tipo de dado não armazena valores negativos;
* Not null (NN): o campo não pode ficar vazio;
* Default: define um valor padrão para inicialização;
* Auto-increment (AI): o campo é preenchido automaticamente;

## Normalização de Dados 
### Relacionamentos e Chaves 
Relacionamento = Ligações entre Tabelas 
* Chave Primária (Primary Key, PK): Coluna com valores únicos;
* Chave Estrangeira (Foreign Key, FK): Coluna que armazena a chave primária de outra tabela;

### Tipos de Relacionamentos 
* Relacionamento 1 para 1 (1:1);
* Relacionamento 1 para muitos (1:*);
* Relacionamento muitos para muitos (*:*); 

## Criando um Banco de Dados 
### Primeiro comando MySQL: 
`CREATE DATABASE curso_sql;`
### Para selecionar o banco criado: 
`USE curso_sql;`

## Manipulando Dados 

## Relacionamentos e Visões 

## Funções Especiais e Subqueries 

## Controle de Acesso 

## Transações ACID 
* Atomicidade;
* Consistência;
* Isolamento;
* Durabilidade;

## Stored Procedures e Triggers 
### Stored Procedures - blocos de código SQL armazenados no banco: 
### Vantagens 
* Centralização;
* Segurança 
* Performance;
* Suporte a transações; 

### Triggers (gatilhos) - eventos que disparam códigos SQL: 
* Execução de cógido SQL baseado em eventos; 

### Tipos de Triggers:
* BEFORE INSERT;
* BEFORE UPDATE;
* BEFORE DELETE;
* AFTER INSERT;
* AFTER UPDATE;
* AFTER DELETE;
* TEMPORAIS

## O curso completo gratuito encontra-se disponível em: https://www.softblue.com.br/
