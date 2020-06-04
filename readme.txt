urls:
See here "test the application"
https://spring.io/guides/gs/accessing-data-rest/

Cool u can do all with post man too, and delete things (but maybe it cause also security breaks 

http://localhost:8080/people

serach

http://localhost:8080/people/search/findByLastName?name=mash



To connect he cURL 

U need to work on 



curl http://localhost:8080/people


Create new : 

 curl -i -H "Content-Type:application/json" -d '{"firstName": "Frodo", "lastName": "Baggins"}' http://localhost:8080/people


http://localhost:8080/people/search/findByLastName?name=mash
