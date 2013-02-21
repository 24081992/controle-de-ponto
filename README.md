## controle-ponto-eletronico

[![Code Climate](https://codeclimate.com/github/thiago-sydow/controle-ponto-eletronico.png)](https://codeclimate.com/github/thiago-sydow/controle-ponto-eletronico)

Controle pessoal de horas para quem utiliza ponto.

Dispon�vel gratuitamente em [http://controle-de-ponto.herokuapp.com](http://controle-de-ponto.herokuapp.com/)

## Utilizando localmente
Se voc� quiser utilizar em sua pr�pria m�quina basta baixar o projeto. Ele utiliza o banco de dados MongoDB e portanto percisa de uma inst�ncia rodando localmente. Baixe em [http://www.mongodb.org](http://www.mongodb.org)

# Configurando a aplica��o
Execute o Bundler

    bundle install

(Opcional) Execute o MailCatcher
	
	mailcatcher

A gem MailCatcher intercepta os emails que a aplica��o envia, e podem ser visualizados no endere�o http://localhost:1080

Execute o server
	
	rails server

Acesse em [http://localhost:3000](http://localhost:3000)

## Licen�a
MIT License. Copyright 2013 Thiago von Sydow