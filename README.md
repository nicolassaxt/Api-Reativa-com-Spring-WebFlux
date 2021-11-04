Uma Api Reativa com Spring WebFlux: Desafio Dio

Executar dynamo: 

 java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
 aws dynamodb list-tables --endpoint-url http://localhost:8000


swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html

Documentação Postman: https://documenter.postman.com/preview/17952036-a04cca3f-29ae-4dc8-b9d0-9b4cd483ab17?environment=&versionTag=latest&apiName=CURRENT&version=latest&documentationLayout=classic-double-column&right-sidebar=303030&top-bar=FFFFFF&highlight=EF5B25
