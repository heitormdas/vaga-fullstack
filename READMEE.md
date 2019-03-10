﻿# pokemon---node

Projeto tambem publicado no npm, para baixar use o comando "npm install heitor_moura".
e não esqueça de copiar os arquivos para raiz, se baixou pelo npm, siga a partir do
segundo passo (o segundo passo é feito só para garantir que a lib do knex esta instalada)



para executar esse projeto, siga as instruções do arquivo README

Antes de rodar o projeto, crie uma base de dados com o nome "pokemon" no mysql

Para executar o projeto, rode os comandos a seguir no console na pasta do projeto;

npm install          \\ comando para instalar as dependencias do projeto

npm install knex -g  \\ comando para instalar o knex de forma global

knex migrate:latest  \\ comando para criar as tabelas na base de dados. obs:ele ira procurar a                      
                     \\ base no mysql na porta padrão (3306), caso deseje alterar, altere o                           
                     \\ aquivo "knexfile.js"

knex seed:run        \\ esse comando ira inserir 50 registros no banco. obs: as inserções estão   		     
                     \\ no aqruivo "pokemon.js" na pasta "seeds"
