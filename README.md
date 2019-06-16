# apiCorrida

utilizar: java version "1.8.0_211"

Instalar o MongoDB 3.4.20 e criar o diretóerio C:\data\db
No diretorio de instalação do MongoDB Server\3.4\bin> Execultar o Mongo.exe e Mongod.exe

Importar o projeto Maven e selecionar a opção Import Existing Maven Projects. Para garantiar realizar o maven update para realização do build do projeto.

selecionar o arquivo "/spring-server/src/main/java/io/swagger/Swagger2SpringBoot.java" e realizar o start da aplicação Run As/ Java Application.

Após start do server

Acionar o a url: http://localhost:8090/race-api/v1/swagger-ui.html

as funcionalidade e massa de testes pode ser acionados por esse portal ou pelo "Restlet Client (http://localhost:8090/race-api/v1/race) METHOD: POST" para consumir o json: https://github.com/desafioRubensLopes/apiCorrida/blob/master/results.json

é possivel conferir a inclusão usando os seguintes comandos no MONGODB.

"> use db"

"> db.tcorrida.find()"

"> db.tresultado.find()"



Qualquer dúvida entrar em contato.
