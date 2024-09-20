# Back End: Node.Js

##  Oque seria Back End?

Back-end é a parte de desenvolvimento de software que lida com o que acontece "nos bastidores" de um site ou aplicação.

#### APIs: 
Pontos de conexão que permitem que o front-end se comunique com o back-end para enviar e receber dados.
Segurança: Inclui autenticação, autorização e criptografia para proteger informações. 

## E oque é Node.js?

É um interpretador Javascript que não depende de navegador, tendo o motor V8 que executa JavaScript rapidamente convertendo-o em código máquina e o Libuv que conecta o Node para o banco de dados.

## Como instalar?

- Pesquise https://nodejs.org/pt em seu navegador e instale:
- Ao instalar confira se foi realmente instalado entrando em seu terminal e escrevendo "npm -v".

## Como usar?

- Crie uma pasta 
- Entre no terminal e mude o diretório escrevendo CD (e o nome da pasta)
- Abrir o editor de texto
- Escrever nome do arquivo no terminal
- Ao entrar faça oque preferir
 
## Express

- No terminal escrever "npm -y"

No editor de texto escrever:
- const express = require ("express");
- const app = express ();

- app.get("/", function (req, res){
- res.send ("escrever oque preferir");
- })
Caso queira ter outras tragetórias se APIs escreva:
- app.get("/escrever oque preferir", function(req, res){
- res.send ("/escrever oque preferir");
- )}

- app.get("/escrever oque preferir", function(req, res){
- res.send ("/escrever oque preferir");
- )}
- Parametros: /:
ex: app.get('/ola/:cargo/:nome/:cor', function(req, res){

})

## Conexão com o MySQL

- Criar pasta
- No terminal escrever = cd 'área de trabalho'
- Escrever o nome da pasta
- Mkdir BackEnd
- npm init -y
- ls 
- Code.
- package.json = colocar seu nome e salvar 
- Criar arquivo "index.js"
- Abrir no terminal o arquivo "index.js
- Escrever no terminal = "npm install"
- Escrever no terminal = "npm i express"
- No arquivo "index.js" escrever = const express = require ("express")
-------------------------------------------------------------------------------------------
Para criar banco de dados:
- const MySQL = require ('mysql/promisse')
- const conexão = mysql.createPool
- database: "nome de sua tabela",
- host: "localhost",
- password: "senha",
- user: "root"
-------------------------------------------------------------------------------------------
- const App = express()
- App.listen(3000)
- App.get("/filmes", function (req, res){
- res.send("")
- })
- abre workbench, clique(+), coloque um nome
- no terminal: mysql -u root -p
- senha: coloque a senha
- use "nome da tabela"
- show databases;
- create databases "nome da tabela"
 
