# NestProject
This repository is dedicated to Nest.js studies.

npm i -g @nestjs/cli --> instala o nest e as dependências
npx nest new nome-projeto --> cria um novo projeto nestjs
escolher npm
cd nome-projeto --> para acessar o projeto na pasta
npm run start:dev --> inicia servidor
npx nest g res users --no-spec --> instala as pastas para criação e CRUD de Users
escolher API Rest --> escolher o tipo do projeto
escolher generar crud --> para gerar o CRUD do User
npm i @nestjs/typeorm typeorm sqlite3 --> instala o typeorm para usar o banco de dados (sqlite3) com o nest
npx nest g res products --no-spec --> instala as pastas para criação e CRUD de Poducts

--------------------------
npx nest g res (nome da pasta entidade) --no-spec
Ajustar o .entity.ts
Ajustar o service.ts cpm ps Objects do Repository
Ajustar o DTO
Ajustar o .module com o import do TypeORM