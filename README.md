# APICarro
API com Node.JS e MySQL - CRUD

Para rodar:
No terminal para testar a conexão: npm start

Para para realizar o teste da API do CRUD
Entrar nesse link: https://resttesttest.com/

<h2>GET</h2>

GET - Endpoint <br>para ver todos os carros no get: Method: GET http://localhost:3000/api/carros<br>
<br>GET - para ver individual: http://localhost:3000/api/carro/(Codigo do carro escolido)<br>
<br>clique em (Ajax request) para ver os carros<br>

<h2>POST</h2>
POST - para inserir: Method: POST
http://localhost:3000/api/carro

Clique duas vezes em (Add parameter)
<br>
<br>primeiro parameter<br>
Parameter Name: modelo<br>
Parameter Value: o que você escolher<br>
<br>segundo paramenter<br>
Parameter Name: placa
<br>Parameter Value: o que você escolher<br>
<br>clique em (Ajax request) para inserir o carro<br>

<h2>PUT</h2>
Endpoint - http://localhost:3000/api/carro/(Codigo do carro escolido)<br>
Com os parameter digitados para alterar<br>
clique em (Ajax request) para alterar o carro<br>

<h2>Delete</h2><br>
Endpoint - http://localhost:3000/api/carro/(Codigo do carro escolido)<br>
clique em (Ajax request) para deletar o carro<br>

se tudo der certo no delete vai mostrar a mensagem como <br>
HTTP 200 OK<br>
{"error":"","result":{}}<br>

