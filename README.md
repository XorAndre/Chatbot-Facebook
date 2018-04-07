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

<script src="https://gist.github.com/XorAndre/2c881c26f55aaa97c7c88fdf1b89d8e3.js"></script>

<br>
### Quarto passo começando o código 
Crie um arquivo index.js e nele insira os seguintes códigos:
<br>

<script src="https://gist.github.com/XorAndre/9e6781754513203b0f58fc5a173fab11.js"></script>

<br>
Os códigos são resposáveis pela inclusão dos pacotes e pela porta do servidor local onde irá rodar nosso teste, que no caso nada mais é que a porta 3000
<br>
### Quinto passo 
Precissamos agora processar os dados e para isso iremos fazer o seguinte: 
<br>

<script src="https://gist.github.com/XorAndre/9d8f00ce7910b6fe552d6ca43ac85f15.js"></script>

<br>
