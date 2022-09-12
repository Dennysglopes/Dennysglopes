REATE DATABASE IF NOT EXISTS db_blog;

USE db_blog;

CREATE TABLE tab_clientes(
	id integer auto_increment primary key,
	nome varchar(100),
	crm varchar(20),
	telefone varchar(20),
	especialidades varchar(10),
	foto varchar(200), 
	data_cadastro timestamp default CURRENT_TIMESTAMP,
	data_alteracao timestamp
);
