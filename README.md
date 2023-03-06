# Estão Servidos?

> #### Projeto Individual - Módulo 3 - Resilia Educação <p> Tema escolhido: Basketball :basketball:</p>

## Status: 
> Complete ✅

## Tecnologias utilizadas :computer:

> ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

## Contextualizando o projeto :clipboard:

<p>Você foi escolhido para desenvolver um servidor de teste
que será usado nas aulas, este servidor terá que ser criado
usando a biblioteca Json-server juntamente com o node.js.</p>

<i>O termo “Json-server” é utilizado para descrever um servidor de testes (pode
também ser correlacionado a um garçom) que serve dados no formato Json.</i>

## O que é para fazer? :pencil:

<p>Neste projeto, você irá desenvolver um servidor json
(Json-server) onde irá conter 2 ou mais rotas com 3 ou mais dados nas quais
o usuário poderá realizar os métodos GET, POST, PUT,
DELETE.</p>

## Como executar o projeto? :arrow_forward:

* Para executar o projeto, você deverá ter instalado em sua máquina o node.js e o npm.
Após a instalação do node.js e do npm, você deverá instalar o json-server.

* Para instalar o json-server, você deverá executar o seguinte comando no seu terminal:
npm install -g json-server

* Após a instalação do json-server, você deverá executar o seguinte comando no seu terminal:
json-server --watch ./mock/db.json
    <p>Onde db.json é o nome do arquivo que você irá criar para armazenar os dados.</p>

* <p>Para acessar o servidor, você deverá acessar o seguinte endereço:
  http://localhost:3000/</br>
  Onde 3000 é a porta que o servidor irá rodar.</p>

## Explicando o projeto :question:

* O projeto possui 3 rotas que são: /players, /treinadores e /estadios.<br/>

>A rota /players possui 7 dados, sendo eles: id, nome, numeroCamisa, clube, posição, conferencia e estatisticas.</br>
A rota /treinadores possui 4 dados, sendo eles: id, nome, clube e conferencia.</br>
A rota /estadios possui 4 dados, sendo eles: id, nome, cidade e capacidade.

### Para acessar os dados, você deverá acessar o seguinte endereço:

>http://localhost:3000/players

>http://localhost:3000/treinadores

>http://localhost:3000/estadios

### Para utilizar o método GET, você deverá acessar o seguinte endereço:

>players/list

>treinadores/list

>estadios/list

### Para utilizar o método POST, você deverá acessar o seguinte endereço:

>players/create

>treinadores/create

>estadios/create

### Para utilizar o método PUT, você deverá acessar o seguinte endereço:

>players/update/:id

>treinadores/update/:id

>estadios/update/:id

### Para utilizar o método DELETE, você deverá acessar o seguinte endereço:

>players/delete/:id

>treinadores/delete/:id

>estadios/delete/:id

Onde :id é o id do dado que você deseja alterar ou deletar, basta substituir o :id por um número.

### Espero que gostem do projeto, qualquer dúvida, estou a disposição. :wink:
## Contato
<a href="https://www.linkedin.com/emerson-pg/" target="_blank">![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)</a> 

## <a href="https://www.instagram.com/yosoygaldino/" target="_blank">![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)</a> 

:copyright: Desenvolvido por Emerson Galdino 2023
