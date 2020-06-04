urls:
See here "test the application"
https://spring.io/guides/gs/accessing-data-rest/



http://localhost:8080/people


To connect he cURL 

U need to work on 



curl http://localhost:8080/people


Create new : 

 curl -i -H "Content-Type:application/json" -d '{"firstName": "Frodo", "lastName": "Baggins"}' http://localhost:8080/people

