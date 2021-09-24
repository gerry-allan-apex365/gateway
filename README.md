# Zuul API Gateway for routing traffic to the User microservice
As part of the Java developer technical assessment, this project holds the Netflix Zuul API gateway.

The API gateway has a sample filter that performs logging before re-routing to the users microservice.

The users microservice can is available for assessment at [Assessment](https://gitlab.com/gerry/assessment)

To run the project: mvn spring-boot:run

The gateway is available at http://localhost:8080 and to access the assessment microservice you append /assessment/ ... 

Example http://localhost:8080/assessment/user/get/all should return a JSON of all users in the database.

