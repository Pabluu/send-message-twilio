# Projeto Send Message Twilio
Projeto criado a partir de uma aula do bootcamp Tech Academy - StartSe.
O mesmo tem o intuito de mostrar uma simples solução de envio de _sms_ usando o [NodeJs](https://nodejs.org) e o [Twilio](https://www.twilio.com/).

## Requisitos
1. Tenha instalado o [NodeJs](https://nodejs.org/en/download/) e o gerenciador de pacotes [NPM](https://www.npmjs.com/).
2. Tenha uma conta no [Twilio](https://www.twilio.com/) e registre um numero de celular( que irá receber o seu sms ).
3. Instale algum software que te possibilite manipular requisições de API. Neste projeto eu utilizei a extensão _Thunder Client_ do VSCode.

## Passos para rodar a aplicação.
1. Clone o projeto: `git clone https://github.com/Pabluu/send-message-twilio.git`
2. Acesse o diretório do projeto: `cd send-message-twilio`
3. Instale os pacotes dependentes: `npm install`
4. Faça uma copia do arquivo `.env.example` e renomeie para `.env`
5. Seta as variaveis do arquivo `.env` de acordo com a sua conta do [Twilio](https://www.twilio.com/)
6. Rode o projeto: `npm run dev`