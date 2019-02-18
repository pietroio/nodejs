# Integração do Express

Crie um diretório para seu projeto:

$ cd ~
$ mkdir projeto
$ cd ~/projeto

Inicie um projeto e salve o pacote da API no diretório:

$ npm init
$ npm install -s express

Agora crie seu código, crie um arquivo com a extensão ".js" (exemplo "app.js"):

$ nano app.js

No corpo do arquivo inscreva:

var express = require('express');
var app = express();
var port = 8000;

app.get('/', (req, res) => {
  res.send('Express rodando');
});

app.listen(port, function() {
console.log(`Express rodando em http://localhost:${port}`)
});

Agora vá até o navegador (browser), e navegue até o endereço indicado no terminal.

Pronto, você agora implementou um simples exemplo do Express. Agora crie seus próprios projetos.
