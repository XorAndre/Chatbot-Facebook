# Chatbot-Facebook
## Chatbot Facebook com NodeJS
<br>
 Neste tutorial ensinarei como criar um Chatbot nativo para Facebook. Alguns detalhes são importantes para que você possa fazer o projeto 100%, são eles: ter o NodeJs e um editor de código instalados em sua máquina. O restante baixaremos no decorrer do tutorial.
<br>
### Primeiro passo 
 Crie um diretório com nome chatbot, feito isso abra o diretório no terminal com o seguinte comando: cd caminhododiretorio/chatbot/.
<br> 
### Segundo Passo
 No segundo passo escreva no terminal o comando: npm init, este comando criará um package.json. Após digitado aperte enter e responda as perguntas feitas.
<br>
### Terceiro Passo
 Agora baixaremos alguns pacotes que colocarão nossa aplicação em funcionamento são eles: Express, body-parser e request. O comando para baixar é: 
<br>

npm install express request body-parser --save

<br>
### Quarto passo começando o código 
Crie um arquivo index.js e nele insira os seguintes códigos:
<br>

```js
'use strict'
const express =  require('express')
const bodyParser = require('body-parser')
const request = require('request')
const app = express()
app.set('port', (process.env.PORT || 3000))
````
<br>
Os códigos são resposáveis pela inclusão dos pacotes e pela porta do servidor local onde irá rodar nosso teste, que no caso nada mais é que a porta 3000
<br>
### Quinto passo 
Precissamos agora processar os dados e para isso iremos fazer o seguinte: 
<br>

```js
app.use(bodyParser.urlencoded({extended: false}))
app.use(bodyParser.json())
```

<br>
