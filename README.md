
# Demo sobre live coding da digital innovation one - spring webflux - criando seu gerenciador de herois

## Stack utilizada

  * Java17
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * sl4j
  * reactor

### Executar dynamo: 

* Na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
* Para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000

* Documentacao gerada pelo postman: https://www.getpostman.com/collections/7595a647c18aabae89d3

### Links úteis da aula:
* Slides de palestra: https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux
* Palestra garavda: https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s
* Site da DIO: https://digitalinnovation.one/
