# APICarro
API com Node.JS e MySQL - CRUD

Para rodar:
No terminal para testar a conexão: npm start

Para para realizar o teste da API do CRUD
Entrar nesse link: https://resttesttest.com/

<h2>GET</h2>

GET - Endpoint para ver todos os carros no get: Method: GET http://localhost:3000/api/carros
GET - para ver individual: http://localhost:3000/api/carro/(Codigo do carro escolido)
clique em (Ajax request) para ver os carros

<h2>POST</h2>
POST - para inserir: Method: POST
http://localhost:3000/api/carro

Clique duas vezes em (Add parameter)

Parameter Name: modelo/ Parameter Value: o que você escolher
Parameter Name: placa / Parameter Value: o que você escolher
clique em (Ajax request) para inserir o carro

<h2>PUT</h2>
Endpoint - http://localhost:3000/api/carro/(Codigo do carro escolido)
Com os parameter digitados para alterar
clique em (Ajax request) para alterar o carro

<h2>Delete</h2>
Endpoint - http://localhost:3000/api/carro/(Codigo do carro escolido)
clique em (Ajax request) para deletar o carro

se tudo der certo no delete vai mostrar a mensagem como 
HTTP 200 OK
{"error":"","result":{}}

