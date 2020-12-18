# AV2-Memes

Integrantes: Igor Galvão de Melo - 1123
Thaisa Borsato Lopes - 1408

>Aplicações necessárias para o desenvolvimento do software:

>Restify: framework para desenvolvimento de aplicações Web, dando auxílio ao tratamento de rotas.
>Mongoose: ferramenta utilizada para modelagem de objetos para banco de dados não-relacional.
>MongoDB: bando de dados não-relacional orientado à documentos.
>Dotenv: Carrega váriaveis de ambiente de um arquivo .env.
>JWT: sistema de autenticação - Token.
>Axios: cliente HTTP que funciona tanto no browser quanto em Node.JS.
>Postman: teste de APIs.
>Docker: de alto desempenho, cria, teste e implementa aplicações em ambiente
separado da máquina original, o container.

>Instalação e configuração:

Ao realizar a clonagem do repositório, é necessário executar o comando abaixo
para instalar as dependências:

>npm install

Para iniciar o servidor, executar o comando abaixo:

>npm start

Para criar a imagem docker (através do Windows Power Shell):

>docker build -t "nome_da_imagem" .
>docker run -d --name "nome_do_container" -p 8000:5000 "nome_da_imagem"

Teste de endpoints:

Importar o arquivo de collections no Postman e executar o 
teste das rotas. 
